# Пробное
## Сегодня установили Ionic на VSCodium c помощью, создали приложение из шаблона:
```
npm install -g @ionic/cli
ionic start
```
## Закрепили за проектом, создали и запустили:
```
git clone https://github.com/starzhstudy-lab/2.git

npm instal l

ionic serve
```
## Седлали массив с названиями 
```
 mylist: string[] = ["Rose", "Teya", "Erika"]
```
## И вывели его в приложении
```
<ion-list>
  <ion-item *ngFor="let el of mylist">
    <ion-label>{{el}}</ion-label>
  </ion-item>
</ion-list>
```
## Весь код сворован из (и отредактирован):

[Документация](https://test-bc740.web.app/api/list)