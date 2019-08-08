# groovy-snapcraft

Making the snap:

```
$ snapcraft clean                       # if needed
$ snapcraft snap --debug
```

Publishing the snap:

```
$ snapcraft push --release=3.0/beta --release=beta groovy_3.0.0-beta-3_all.snap
$ snapcraft push --release=2.5/stable --release=stable groovy_2.5.8_all.snap
```

Installing the snap:

```
$ sudo snap install --classic --dangerous groovy_2.5.8_all.snap
```
