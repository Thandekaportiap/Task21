<img src="https://socialify.git.ci/Thandekaportiap/Task21/image?language=1&owner=1&name=1&stargazers=1&theme=Light" alt="Task21" width="640" height="320" />

<h1>MongoDB- Task21</h1>

Start the MongoDB Shell
```bash
 mongosh
```
Create a MongoDB database 
```bash
 use <Database-Name>

```
Create a collection
```bash
db.createCollection("<Collection-Name>")
```
Insert a document
```bash
db.<Collection-Name>.insertOne({
  <Field-Name>: "<Value>",
  <Field-Name>: "<Value>",
  <Field-Name>: "<Value>"
})
```
Exit the MongoDB Shell
```bash
 Exit
```
To export the database
```bash
mongodump --db <Database-Name> --out /path/to/export/directory
```


