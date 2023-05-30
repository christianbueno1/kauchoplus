# kauchoplus website

## container podman

```
./createsite.sh christianbueno1/wordpress:6.2.2-php8.0-apache \
"" mariadb:10.6.13-focal "" "" var-www-html var-lib-mysql

user
group
other
#
sudo chmod -R o+w _data

```



```
gh repo create kauchoplus --public \
-d "kauchoplus, container, podman, website." \
--source . \
--remote origin

gh repo view kauchoplus

```