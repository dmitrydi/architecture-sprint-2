# pymongo-api

## Как запустить

Перейти в директорию с решением

```shell
cd sharding-repl-cache
```

Запускаем mongodb и приложение

```shell
docker compose up -d
```

Регистрация сервисов и заполнение базы данных значениями. Перед запуском скрипта необходимо подождать около минуты, пока инициализируются все сервисы в docker-compose.

```shell
./scripts/start.sh
```

## Как проверить

Откройте в браузере http://localhost:8080


## Ссылка на схему
```
https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=sprint-2-shard-repl-cache-gateway-cdn.drawio#R%3Cmxfile%3E%3Cdiagram%20name%3D%22Page-1%22%20id%3D%22-H_mtQnk-PTXWXPvYvuk%22%3E7V1Zk9q4Fv41%2FeguyfL62FsmqZrM5KaTmuUl5QY3eAYw17i3%2FPrxCvaRsIVtyYLmhUXYAo4%2BfefoLNIFuVm%2B%2FhJ56%2FnncOovLnQ0fb0gtxe6bhBkJU9py1veotvYyVtmUTDN2%2FCu4T746ReNqGh9Cqb%2BpnZhHIaLOFjXGyfhauVP4lqbF0XhS%2F2yx3BR%2F9a1N%2FOphvuJt6Bb%2Fwim8bxoxZa7%2B%2BCjH8zmxVc7up1%2FsPTKi4t%2Fspl70%2FCl0kTuLshNFIZx%2Fmr5euMvUumVcsnv%2B7Dn0%2B0Pi%2FxVzHPDZI1mv7ma9v3v5d%2BusfzfP%2F5fM80x8m6evcVT8Y%2BLXxu%2FlSKIwqfV1E97QRfk%2BmUexP792pukn74ko560zePlInmHk5dFd34U%2B697fyje%2Fv0EOH649OPoLbmkuEE3CokVmLHd4v1LdQDMonFeEb5pFY1eMeqzbec7wSQvCtkcICfTVF9Oxvhicg%2BREpYiJdeCUqLFRAhDSlgXJSVLfSlhxpwTJ6WfVzr5HH77vvn2wfjh4th5Dr5rOiWlz%2BFqFt5eX5CrnE6jKf6BKdElH6zTl5O3RZDIMCLtAnzIpf3rw7bBm%2Fw7y8bg96c46cYv2je5fsLmVuqUiBkDsV%2Fqdl3qW61XkbrNELojSuaEkvn6bZlKXfPWwRAg7SUuguriIiahGU9nyGsIvvuDvDx%2BfPY%2FrmdP%2BNb7NP%2F67fpew5S8MowmTV%2FDp9iPMqha3jKVxephkz5l4tz8iPLPB9AhvURqW1CkDCViyBQpz7TXT2vaGxKnPVPm9LQvYXwTrh6DWSppP3ou8Jza2knjffSsHHwxGRu%2BHHaiv5pepSuTFKwLb7MJJnW51IXovwbxn%2BnrS8O2ivd%2FJe81dIl0o2i4fa1cfftWefPFj4Lkn6VDl7etkn9Z9qeXDWmH%2BBIhp2zYdZi9e6u%2Bg13uHcdN%2BBRN%2FHb6jL1o5sft%2BPSntbUajYrKqDPt3qIt8hdeHDzXV3gsJBTf8CUMkn%2B2BZ1jAq1tAjDl%2F7u4q7oiAx25QJ%2FpCHSUC4bqKAPm9m93xyqHHVrB6ipM%2BbAdqLgCUnRpNiK0N3RODhIE6GPI%2BYIhYQ9OX1u%2BqXJNgYtDmSYd7fvil4RRPA9n4cpb3O1a9wOqyjFNyw1FANWKA25AOUBDwvXaHkAlQ%2By9VS5bpxdsGn6wCX8wbv5de2bMDs%2F5LxgU3c57QHeTVa0KuimwDKRBDUnoNmSgFe9ZXQIPCI3hI1oKYQT4SaYLhC11Pr8TOWqpb917ykh9zxIULPtPC%2Bujr%2FsxHf1hSf20sC5T6kz3P03rfFbIJlFmcQfPQbqwr3oOEvPEbl6WNTsOgKljdzJ2mPZIt6WgzmkD5Rwzls2DEQjXEeiD4jV6MAKIJpjP6ulgmDABTGvIM4APCLlJwhuGNmtnvFEMCnsSjDeOHIUz3kbHG%2BQ33XAvna4MB1cFdF%2BCMdfVj3%2FG3Jgc1wdz1JpIOuZKNV4BXWaBJ010vDMxf%2BM6sLxFMFulqEsGJx3C69RIDibe4qr4YBlMp5kfiWWq12F5wbayD0kpwQj4MLcWdQUcFgMcRJjhTVvepXzp2X188jUYOTty5Usbhl%2F9abBJmibeZO4zsiGi9HNGNF92%2FpMBTWpGMp3Oyn8StkrUaTLg00BckWSjompwDzWTdFXXNK7bKYbM6%2FseZMHIGxIadb1oAxOIwOAwr2JzIA3D2ORAPnJHt2rfYxLU%2BLuI2Xh9b586e1Z1db7snVX8uKzirYE%2FxwKchUzmePQGHOXoEO2e6Oqf4GFOXa8Z6TujvRN7YreWgpPm9HTLwRHFn01Zou0Ot1H5E2Y2ul3hjPeYBgPzJzFxnaeNZv60HbvpekH8Scdp%2Bs6t3Www9botgZDdZS6cDiMD5OkQeaIhPBhqunrweBjZrSacZQzaIysydcOYdRQaO1iqwMhNFSV8iZTvlpEHg7OwJN8UfnUDw7CcPgZGHcttOJYJWfcMWQFGBCbQKVSssva6PeENbrPVAY17V4bRwZGVKr1gzq6vlnau6PHqCnWO%2FMax5eQyHGuyxURXqapYWdhP7A4Qu0WLXWrSSznE4koLe8mLYDidkcTaQrbEVCgu7CVUm%2BJIRu21sPIstlBp35CK5YWDzn2MR5%2F8YxYYDgphhxHDlIxgkWtppSsMqWVH6xqD8Pp5SoAqk9ngWGAOo67hHxdoNpcz%2FDOU8U4OWyyLqzLsDp9TRIUBdQSM9oiGxWHFp6rWYlGgaqWacvWhDKjaocANKhcoS5sPUwdXY8FpgElLseG%2BeSPUbUFOo5j2cIiXRrY6EKcBM5A2xVgWxnUpkKU9SCqWHPbMm3NV843wOaTGLsPqJ3UdKSb1ctWmeMnhsFgf3xdg8FQ1j19zOCzYFRA77fjiM0beQ0FD%2B0pQ5zR9SlJRxvTByIRQhNWC%2FBUSENVIdiFY1%2Byj9wBidSCHKdu1M%2BQoIqW6Eg25c%2FHhMUAOspzr9ig%2BhOsDui%2FRoDtXHx4D6CDP9QEdtTySDzraI3vU1YfQrYkYe4NKLY8zaH%2FgUZcfQgGzNqCXK2Dae3Us9YcmZVozijnlFiAaHJv5nwsQhwxCq7Z2tKHzCHXd1tShyJhzq9uDixBL99KWlJyWKkS7%2BQYxfvZSjsLLENsdFo5ioLPKJDs4IP1BR3k%2BRO8hMnix6QkXIrbzKOLlUdUWCnQeZOdCLn2fmTB0MaJVL85228oCShOWfb0gFtUHn1%2ByihGPkZfhAlU2hgeDzfA1rKdbjdhKy2XRyfHlWCpAy4NBWlhS8JFWJLbD1j7DVpo1gQnlK0JtZYngDqdlNwRo7DsydkNwaJfp1ZdP95%2F%2BTNp%2B8WL%2FxXujpqHsCgZNB1tbmQw%2FKGGVMFDFroO5lpzhMyM7pIVXSAkhAtSsLjensksFtcOo%2Bm84vHQ0vgILeqdrzroNjk2zJVcyOOKOD8kMRQyiZjrpBMG9its0OyhuJQGdn1o8WtwPbDpqd00mHh3QtIf%2FJlxtnhbqKS2NVTYuV2mVHY%2BstFonZEWtJdAETgyMu3DKkHPc4J3j7phz3NlnNB06xzUM1J%2FG64U%2B2Mg2oecc2c02M3WHhluiJRp27cY7xNjZ22L86txLkHmF0sdrM3sk2aNzkUwnB2ePevaYX4Oy11blmg%2F07E0A%2Fqv34C%2B6Bt4jfxP89B6y%2FtJ5UwxZ0rl5fWHeNnHjJFyt%2FElc3Jy0MYKBDbS0l0nRJbHKTduKMSP9Zkh5Sfj4uPGF6CVXWNyk4%2FLAIod5LUZfGpTZcO%2BFZV1w9oDBeWzmwRxrwA2h9BaKhTdouGVbXM02Gm8QxbAMD%2BKZYSt01MCwiQ506%2FBTnmF1arQnheWP%2Fh1%2F1w0NnsVgMs7sYu7GQxV2Dmf%2BC4wamVW1xKuUDAuEhtxdDH8k476EleJqhwCz1%2BgayiRgAW9I3ogSI3oep%2FzrfshY%2BC57vM64mGSPdoWdc%2B5Ovjij7yucffShTvHbTq6yy7aNZoX3darlrmg%2FDfbfswHljv1tW3W63xZu1cjLWmQZxrg2SNb%2Fn8K0eZkgN1hpcbjOyzLR%2BjUTb%2Fl58mqWPadwc7IBv60bBrlJUGnP8sjzL03%2BRfq9RRdF47psuKxctt5dBdBEZ0izFFOYYOFxkVHyPIGRv6JoeAB9pYPqE0axZ7lOlrTHIUas%2FVXkj7j%2BTkbc0RUYcgW3SdV2SZeU%2F6uq7FmisoTtoYYRHcq5uf2tQVqy7F5kQmnx4gqaHgMKi1EIkHLAVTbL87nujC87eGCOCqJjnOi2xz67yV7bNftpt6re2liV66HAy%2F0RnpaLq0kcVg2pzOj6Em6COAhTg%2BohjONwybC0MvKvDkyYb5Nwk1tPw%2FFnMjhwR2wGg7LqXcSRAuM07PNgZYPl7PF6jThWDF13HquMBnXlxkpc3gS6NBzKC9IpxCnVPb%2FVC%2B0H0OSWylieEs2Ch%2FpC85U7DmoClx7vxmmDrYGxwHrGAxx4LdmxJixndDqVHUiGM29Q%2FwznweAs8nzQweBs74pxSzgfAzvz5oaf4TwcnBkx%2F73xx60pl1x2jJtTpOFWsFgd%2FWzskj4UiW9lGbHAtMOGqz55IN56qDzbdTzugNliXYNgmgmiYJQ%2FZaDkC82FuRR6Wy6FARPcDr7DLFxbYrMvBByrWU6%2B6tS71DlTnkAqumV0S0VXMnl8dKV9fBPPBK5VS3dafhnli7Va5p0DFeLBd0hJRBVwkunOWiYuWPwpcAAuGjVTQ7Op6BH0UwmfLcNhh%2BPIixHicwREMhlndMkOzzEOfFQkPAdPM2QdaCY5xsQ69VHB8JwDNzhUQXR7IpvnKAJGBFZss8qGpcYRGEdInkcrn1vwxD8FBovtzzkPlmZTeyGMP1jD%2B34UitC1%2B2xKPdBuDpeWiTK7gWjWYGcbaRY83AhxltEMZiIzDgrtC8QTjNG1A5p7r7wzoAUDWtjGTKcUpeMANLfD4gxosYBmVBLwxelo4B9DnA6MnTP2JvJYwKmSveN0bp0%2Buu5cIzVOx70B3MhxOhN4QK2uZ%2BlosBTZlHx6E2acLjkQdHfR4m2oyzL7HGByacvZp1BspCvH%2BDuG7uEhZhBUsp3aPoWCokqMA0B7Tgx%2BuHGgaNx4qQ1sHrtzvNQAg2sNduZ58jYK0yq53eWJSTL%2FHE7TYte7%2FwA%3D%3C%2Fdiagram%3E%3C%2Fmxfile%3E
```