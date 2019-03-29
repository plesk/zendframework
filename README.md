![Logo](http://framework.zend.com/images/logos/ZendFramework-logo.png)

Welcome to the Zend Framework 1.12 Release! 

USAGE
=====

```
composer require plesk/zf1
```

https://packagist.org/packages/plesk/zf1

HOW TO PREPARE RELEASE
======================

```
git checkout -b 1.12.17-plesk-min-4
docker run -it -v $(pwd):/root/ ubuntu /root/build.sh
git add .
git commit
git push --set-upstream origin 1.12.17-plesk-min-4
git tag 1.12.17-patch4
git push origin 1.12.17-patch4
```
