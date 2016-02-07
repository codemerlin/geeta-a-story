# Geeta a simple story

this uses node/npm harpjs and bower so install all of that first, to be double sure follow the instructions here https://github.com/jvandemo/hb-bootstrap 

```
npm install -g harp
npm install -g bower
```


to run and work on it edit the files under _harp directory and run following command

```
NODE_ENV=development harp server _harp
```
to compile before deploy run following

```
NODE_ENV=production harp compile _harp ./
```
