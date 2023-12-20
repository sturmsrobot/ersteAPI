# Mein erstes API

## Allgemeine Infrastruktur
![](./Infrastructure.png)

## API Dokumentation
`GET /allitems`: Gibt Alle Elemente der Shopping Liste zurück

`GET /itembyid/{itemdId}`: Gibt ein einzelnes Element zurück.
**Parameter**: `itemId` - Einzigartige Id des Elements

`POST /api/newitem`: Erstellen eines neuen Elements **Parameter**: `newItem`: ein neues Element in der Liste

`DELETE /api/items/{id}`: Löschen eines Elements **Parameter**: ÌD des Elements

`PUT /api/items/{id}`: Aktualisierung eines Elements *+Parameter**: ID des Elements
