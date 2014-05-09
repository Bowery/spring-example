## Bowery Spring Example
```
$ bowery connect
$ bowery logs #in another tab
$ bowery ssh web # in another tab
root@138b17bfdcb6:~# cd /application && chmod +x gradlew
root@138b17bfdcb6:/application# ./gradlew build
root@138b17bfdcb6:/application# ./gradlew bootRun
```
Prepend the url you're given with `8080.` and then start developing and you'll see the changes. If you go to `/greeting` you should see a greeting. It should look something like `http://8080.web.536d19502a2d59256c000014.boweryapps.com/greeting`.

As you change files locally, they will be synced as long as `bowery connect` is running.
