# mediaQuery
```
751~: red (min-width: 751)
376~750: green (max-width: 750)
0~375: yellow (max-width: 375)
```

```
		@media (min-width:751px) {
			body {background-color: red;
			}			
		}

		@media (max-width:750px){
			body {background-color: green;
			}
		}	

		@media (max-width: 420px){
			body {
				background-color: yellow;
			}
		}
```

#viewport
```
<head>
	<meta name="viewport" content = "width=device-width, initial-scale=1.0">
</head>
```
