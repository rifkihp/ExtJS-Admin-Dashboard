# ExtJS-Admin-Dashboard

Cara Installalsi:

    sencha --sdk=<Letak SDK/Framework extJs> generate app -s <Letak SDK/Framework extJs>/templates/admin-dashboard Admin admin-dashboard

edit file app.json dengan kode berikut:

    "output": {
		   "base": "${workspace.build.dir}/${build.environment}",
		   "page": "index.html",
		   "manifest": "${build.id}.json",
		   "js": "${build.id}/app.js",
		   "appCache": {
			    "enable": false
		   },
		   "resources": {
			   "path": "${build.id}/resources",
			   "shared": "resources"
		   }
	   },
  
 Selanjutnya jalankan perintah build:
  
    sencha app build --development
  
 Setelah selesai jalankan:
  
    sencha app watch
    
 Jalankan pada browser dengan alamat:
  
    http://localhost:1841
    
 
 Selamat Mencoba.
 
 Terimakasih.
  
