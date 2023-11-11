## Аттестация
{
	"info": {
		"_postman_id": "f8cda841-5a8a-468a-800b-d6e0ab29dc51",
		"name": "New Collection",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "26460349",
		"_collection_link": "https://www.postman.com/lively-capsule-999012/workspace/githab/collection/26460349-f8cda841-5a8a-468a-800b-d6e0ab29dc51?action=share&source=collection_link&creator=26460349"
	},
	"item": [
		{
			"name": "Issue 1",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "{{URL}}issues?apiVersion=2022-11-28&label=bag&assignee=maria.malova@mail.ru&Cookie=token_global={{token_global}}#about-issues.",
					"host": [
						"{{URL}}issues"
					],
					"query": [
						{
							"key": "apiVersion",
							"value": "2022-11-28"
						},
						{
							"key": "label",
							"value": "bag"
						},
						{
							"key": "assignee",
							"value": "maria.malova@mail.ru"
						},
						{
							"key": "Cookie",
							"value": "token_global={{token_global}}"
						}
					],
					"hash": "about-issues."
				}
			},
			"response": []
		},
		{
			"name": "Issue 2",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "{{URL}}issues?apiVersion=2022-11-28&label=bag&assignee=maria.malova@mail.ru#about-issues.",
					"host": [
						"{{URL}}issues"
					],
					"query": [
						{
							"key": "apiVersion",
							"value": "2022-11-28"
						},
						{
							"key": "label",
							"value": "bag"
						},
						{
							"key": "assignee",
							"value": "maria.malova@mail.ru"
						}
					],
					"hash": "about-issues."
				}
			},
			"response": []
		},
		{
			"name": "Issue 2 Delete",
			"request": {
				"method": "DELETE",
				"header": [],
				"url": {
					"raw": "{{URL}}issues?apiVersion=2022-11-28&label=bag&assignee=maria.malova@mail.ru#about-issues.",
					"host": [
						"{{URL}}issues"
					],
					"query": [
						{
							"key": "apiVersion",
							"value": "2022-11-28"
						},
						{
							"key": "label",
							"value": "bag"
						},
						{
							"key": "assignee",
							"value": "maria.malova@mail.ru"
						}
					],
					"hash": "about-issues."
				}
			},
			"response": []
		}
	],
	"event": [
		{
			"listen": "prerequest",
			"script": {
				"type": "text/javascript",
				"exec": [
					""
				]
			}
		},
		{
			"listen": "test",
			"script": {
				"type": "text/javascript",
				"exec": [
					"pm.test(\"Status code is 200\", function () {",
					"    pm.response.to.have.status(200);",
					"});"
				]
			}
		}
	],
	"variable": [
		{
			"key": "URL",
			"value": "https://docs.github.com/en/rest/issues/",
			"type": "string"
		},
		{
			"key": "token_global",
			"value": "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",
			"type": "string"
		}
	]
}
