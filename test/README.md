## knative test manifest

---

ymlファイルを適用
```
kubectl apply -f hello.yml
```
確認
```
kn service list

NAME    URL                                             LATEST        AGE    CONDITIONS   READY   REASON
hello   http://hello.default.<ip address>.sslip.io   hello-00001   152m   3 OK / 3     True
```

