# django-ranged-fileresponse
This is a modified FileResponse that returns `Content-Range` headers with the HTTP response, so browsers (read Safari 9+) that request the file, can stream the response properly.
