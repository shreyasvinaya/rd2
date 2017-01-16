Remote System
=========================


```

Build 
```
git clone repository.git

cd repository

docker build --rm -t containerName .

```

Run
```
docker run -i -t -p 6080:6080 containerName
```

Browse http://127.0.0.1:6080/vnc.html


License
==================

See the LICENSE file for details.
