```javascript
//Level 1,2
	const knowledge = {
		title:'I0 Diagnostics Tests',
		sub:'I0 is a discovery stage where the patients can get their current diagnosis by taking the diagnostics tests. With the results, AFH can offer professional following recommendations and services.',
		description:'At AFH, we offer total of 23 kinds of either in-clinic or outsourcing diagnositics tests to satisfy various demands on different categories from patients.',
		importance:'Predicting potiential risks to personal health is more than important, especially from a younger age. It is an early stage where patients can get precise diagnosis and response quicker to prevent sever diseases.',
		handle:'i0-diagnostics',
		image_url:'https://someimage.png',
		images:['image_handle 1','image_handle 2'],
		audiences:["audiences"],
		services:["association to service"],
		articles:["association to article "],
		references:["association to glossaries"],
		faq:["association to faq"],
		tags:['tag name']
	}

//	 //Level 2 I0 - I4
	const article = {
		title:'Nutritional Wellness',
		sub:'wellmatrix nutritional wellness focus on bring in nutritional balances',
		description:'They are the building blocks and energy sources needed to replace, maintain, and repair your body every day.',
		importance:"To achieve Nutritional Wellness, you must be mindful of your dietary requirements, especially macronutrients, which consist of proteins, fats, carbohydrates, water, and fiber.",
		image_url:'https://some_image.png',
		audiences:["audiences"],
		key_title:'ignoring nutritional wellness will have  seviere consequnces on',
		key_points:["Low energy levels", "malnutrition", "toxins build up", "mood changes", "weak immune system"]
		feature_products:["handle_1","handle_2"],
		compositions:["association to glossaries"],
		references:["association to glossaries"],
		faq:["association to faq"],
		tags:['tag name'],
	}

	const faq = {
		title:'How long has Poly-MVA been in use',
		answer:'Poly-MVA has been available in the U.S. since 1992. The first several years were spent trying to present the scientific data to physicians. There are many physicians around the world recommending and using Poly-MVA in their practices as part of an overall treatment program for general health and well-being.',
		tags:['tag name']
	}

	const glossary = {
		title:'Vitamin A',
		sub:'Vitamin A is retinol. Carotene compounds',
		type: 'nutrient' || 'reference' || 'chart' || 'service',
		nutrient_type:'vitamin' || 'mineral' || 'essential nutrients' || 'phytonutrients',
		service_type: "dianostic" || "treament" || "IV treament" || "consultation" || "injection" || "prescription",
		description:'Vitamin A is involved in immune function, vision, reproduction, and cellular communication [1,4,5]. Vitamin A is critical for vision as an essential component of rhodopsin, a protein that absorbs light in the retinal receptors, and because it supports the normal differentiation and functioning of the conjunctival membranes and cornea. Vitamin A also supports cell growth and differentiation, playing a critical role in the normal formation and maintenance of the heart, lungs, kidneys, and other organs.',
		importance:'Vitamin A is involved in immune function, vision, reproduction, and cellular communication [1,4,5]. Vitamin A is critical for vision as an essential component of rhodopsin, a protein that absorbs light in the retinal receptors, and because it supports the normal differentiation and functioning of the conjunctival membranes and cornea [2-4]. Vitamin A also supports cell growth and differentiation, playing a critical role in the normal formation and maintenance of the heart, lungs, kidneys, and other organs [2].',
		audience:["audience"],
		key_title:'benefit to your body',
		key_points:["improve immune funciton","improve vision"],
		biomarkers:126,
		image_url:'https://someimage.png',
		external_links:['https://some_reference_link.com'],
        tags:['tag name']
	}
```
