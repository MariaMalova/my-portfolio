## Аттестация
{
	"id": "4aeae3ff-eace-4f55-9e44-88bd9b313587",
	"name": "New Collection",
	"timestamp": "2023-11-11T21:49:51.014Z",
	"collection_id": "26460349-f8cda841-5a8a-468a-800b-d6e0ab29dc51",
	"folder_id": 0,
	"environment_id": "0",
	"totalPass": 0,
	"delay": 0,
	"persist": true,
	"status": "finished",
	"startedAt": "2023-11-11T21:49:49.349Z",
	"totalFail": 4,
	"results": [
		{
			"id": "c80f1b0f-305e-4cae-8bca-0e74dfb9fd4f",
			"name": "Issue 1",
			"url": "https://api.github.com/repos/MariaMalova/my-portfolio/pulls?assignee=maria.malova@mail.ru&label=bug",
			"time": 177,
			"responseCode": {
				"code": 404,
				"name": "Not Found"
			},
			"tests": {
				"Status code is 200": false
			},
			"testPassFailCounts": {
				"Status code is 200": {
					"pass": 0,
					"fail": 1
				}
			},
			"times": [
				177
			],
			"allTests": [
				{
					"Status code is 200": false
				}
			]
		},
		{
			"id": "c71b4855-038c-4759-9ee2-0f6c2c00f05b",
			"name": "Issue 2",
			"url": "https://api.github.com/repos/MariaMalova/my-portfolio/pulls?assignee=maria.malova@mail.ru&label=bug",
			"time": 169,
			"responseCode": {
				"code": 404,
				"name": "Not Found"
			},
			"tests": {
				"Status code is 200": false
			},
			"testPassFailCounts": {
				"Status code is 200": {
					"pass": 0,
					"fail": 1
				}
			},
			"times": [
				169
			],
			"allTests": [
				{
					"Status code is 200": false
				}
			]
		},
		{
			"id": "438b85ed-c4cb-4bfb-b03c-1ea841e7340c",
			"name": "Get Issue",
			"url": "https://api.github.com/repos/MariaMalova/my-portfolio/pulls/PULL_NUMBER",
			"time": 169,
			"responseCode": {
				"code": 404,
				"name": "Not Found"
			},
			"tests": {
				"Status code is 200": false
			},
			"testPassFailCounts": {
				"Status code is 200": {
					"pass": 0,
					"fail": 1
				}
			},
			"times": [
				169
			],
			"allTests": [
				{
					"Status code is 200": false
				}
			]
		},
		{
			"id": "c76f99fb-dad8-4402-a384-a72648e42197",
			"name": "Issue 2 Delete",
			"url": "https://api.github.com/repos/MariaMalova/my-portfolio/pulls",
			"time": 169,
			"responseCode": {
				"code": 404,
				"name": "Not Found"
			},
			"tests": {
				"Status code is 200": false
			},
			"testPassFailCounts": {
				"Status code is 200": {
					"pass": 0,
					"fail": 1
				}
			},
			"times": [
				169
			],
			"allTests": [
				{
					"Status code is 200": false
				}
			]
		}
	],
	"count": 1,
	"totalTime": 684,
	"collection": {
		"requests": [
			{
				"id": "c80f1b0f-305e-4cae-8bca-0e74dfb9fd4f",
				"method": "POST"
			},
			{
				"id": "c71b4855-038c-4759-9ee2-0f6c2c00f05b",
				"method": "PATCH"
			},
			{
				"id": "438b85ed-c4cb-4bfb-b03c-1ea841e7340c",
				"method": "GET"
			},
			{
				"id": "c76f99fb-dad8-4402-a384-a72648e42197",
				"method": "POST"
			}
		]
	}
}
