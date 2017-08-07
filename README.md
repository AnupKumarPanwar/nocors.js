# No CORS

A javascript libraray to bypass **cross-origin request blocked** error on GET Request

## Getting Started

Include the script in your HTML file.
```<script src="nocors.js"></script>```

OR

Use the RawGit CDN 
```<script src="https://cdn.rawgit.com/AnupKumarPanwar/nocors.js/539baf4e/nocors.js"></script>```

### Usage

```
nocors(api_url, function(data){
	console.log(data);
})

```

Example

```
nocors('https://www.instagram.com/anupkumarpanwar/media', function(data){
	console.log(data);
})
```



## Acknowledgments

* cors-anywhere.herokuapp.com
