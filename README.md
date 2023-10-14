#### This project is for the Devops bootcamp exercise for

#### "Cloud Basics"

https://registry.npmjs.org/

**** 

### Module 6 exercise

<details>
<summary>Exercise 6: package node app and push to Nexus</summary>

**steps:**

#### login as a user
```cmd
npm adduser --auth-type=legacy
```

#### add to package.json
```json
    "publishConfig": {
        "registry": "http://xx.xx.xx.xx.:PORT/repository/node-apps/"
    }
```

```cmd
npm pack
npm publish
```

</details>