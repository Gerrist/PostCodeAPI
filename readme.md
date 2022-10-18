#PostCodeAPI

Source (c)URl: 

curl 'https://overpass-api.de/api/interpreter' \
-X 'POST' \
-H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' \
-H 'Accept: */*' \
-H 'Origin: https://overpass-turbo.eu' \
-H 'Referer: https://overpass-turbo.eu/' \
-H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/15.6.1 Safari/605.1.15' \
--data 'data=%2F*%0AThis+has+been+generated+by+the+overpass-turbo+wizard.%0AThe+original+search+was%3A%0A%E2%80%9Caddr%3Apostcode%3D*+in+%22The+Netherlands%22%E2%80%9D%0A*%2F%0A%5Bout%3Ajson%5D%3B%0A%2F%2F+fetch+area+%E2%80%9CThe+Netherlands%E2%80%9D+to+search+in%0Aarea(id%3A3602323309)-%3E.searchArea%3B%0A%2F%2F+gather+results%0A(%0A++%2F%2F+query+part+for%3A+%E2%80%9C%22addr%3Apostcode%22%3D*%E2%80%9D%0A++node%5B%22addr%3Apostcode%22%5D(area.searchArea)%3B%0A)%3B%0A%2F%2F+print+results%0Aout+body%3B%0A%3E%3B%0Aout+skel+qt%3B'
