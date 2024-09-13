reflected xss
	دي علشان يتم استغلالها لازم نبعت لينك للشخص المستهدف يكون فيه ال payloads

stored xss
	الصفحه بتخزن الكود في قاعده البيانات فبنبعت ال pdyloads مره واحده بس واي حد بيدخل علي الصفحه بتتنفذ عليه

Don xss
	لا يختلف علي ال reflected لكن الفرق طريقه استقبال البيانات ال reflected بتستقبلها لغه البرمجه الي بيستخدمها الموقع زي ال php اما ال Dom based الي بيستقبل البيانات ال functionبتاعت ال JS


Source Function
	هي دوال تستخدم لقراءه رابط الصفحه بالكامل او عمل تحليل للرابط وقراءه جزء واحد منه فقط
	لقراءه رابط الصفحه بالكامل يمكن استخدام
		document.URL
		document.documentURL
		document.URLencoded
		document.baseURL
		location
		location.href
	لقراءه اسم الصفحه ومسارها فقط
		location.pathname
	لقراءه المدخلات او ال parameters فقط :
		location.search
	لقراءه ال fragments فقط :
		location.hash





Sink Functions
	هي دوال تستخدم لطباعه او كتابه قيم صفحه ال HTML باستخدام جافاسكربت
	Document.write()
	Document.writeln()
	Document."ELEMENT".innerHTML
	
	