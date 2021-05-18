![html](https://www.teaching-materials.org/_deprecated/storage/img/html5logo.png)

# Local Storage
With web storage, web applications can store data locally within the user's browser.

Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

## Web Storage Objects
HTML web storage provides two objects for storing data on the client:

* `window.localStorage` - stores data with no expiration date
* `window.sessionStorage` - stores data for one session (data is lost when the browser tab is closed)
### Example
```
if (typeof(Storage) !== "undefined") {
  // Code for localStorage/sessionStorage.
} else {
  // Sorry! No Web Storage support..
}
```
## Set Item
`localStorage.setItem("lastname", "Smith"); `
## Get Item
`localStorage.getItem("lastname"); `

## Helpful resource:
* [THE PAST, PRESENT & FUTURE OF LOCAL STORAGE](http://diveinto.html5doctor.com/storage.html)
