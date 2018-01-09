## https://markusila.github.io/icofounders/
## The first visualisation graph of connections between ICO Founders and Projects
======


### Projects list

+ Trinity https://trinity.tech

### Founders list

+ David Yiling Li
+ Guangfeng Zhang
+ Fengping Yi
+ Yang Li
+ Will Wei Wu
+ Lola XIE
+ Dominic Yu Zhao
+ JC XU
+ Zhoudong Ji
+ Yanbo Li

### How to contribute?

In order to contribute to the project, please clone the repository, edit this json file:
https://github.com/markusila/icofounders/blob/master/json/neo4jData.json
and ask for pull request.
```javascript
"graph": {
    "nodes": [{
        "id": "1",
        "labels": ["User"],
        "properties": {
            "lastname":"David Yiling Li",
            "twitter": "https://twitter.com/DavidRaiStone"
        }
    },{
        "id": "2",
        "labels": ["Project"],
        "properties": {
            "lastname":"Trinity",
            "website": "https://trinity.tech"
        }
    }],
    "relationships": [{
        "id": "1",
        "type": "FOUNDER",
        "startNode": "1",
        "endNode": "2",
        "properties": {
            "proof": "https://trinity.tech"
        }
    }]
}
```