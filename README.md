POST /payload HTTP/1.1

Host: localhost:4567
X-Github-Delivery: 72d3162e-cc78-11e3-81ab-4c9367dc0958
User-Agent: GitHub-Hookshot/044aadd
Content-Type: application/json
Content-Length: 6615
X-GitHub-Event: issues

{
  "action": "opened",
  "issue": {
    "url": "https://discordapp.com/api/webhooks/276833795343384576/Tut0oP_Adi_rE4D8fa4QCyV-drMYDGzbDhz8I3rjn6JcPYMb7DNrmOxwujzqaa83XXkn",
    "number": 1347,
    ...
  },
  "repository" : {
    "id": 1296269,
    "full_name": "octocat/Hello-World",
    "owner": {
      "login": "octocat",
      "id": 1,
      ...
    },
    ...
  },
  "sender": {
    "login": "octocat",
    "id": 1,
    ...
  }
}
