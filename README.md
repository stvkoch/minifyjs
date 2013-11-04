#README

#minifyjs

Order should be minify:

    ./minifyJs dep1.js dep2.js dep3.js application.js > bundle-min.js



You can minify remote js in one bundle file

    ./minifyJs http://js.sapo.pt/SAPO/0.1/ http://js.sapo.pt/SAPO/Dom/Loaded/1.1/ http://js.sapo.pt/SAPO/Dom/Css/0.1/ http://js.sapo.pt/SAPO/Dom/Event/0.1/ http://js.sapo.pt/SAPO/Dom/Selector/1.1/ http://js.sapo.pt/SAPO/Dom/Element/0.1/ http://js.sapo.pt/SAPO/Utility/Array/0.1/ http://js.sapo.pt/SAPO/Utility/Cookie/0.1/ http://js.sapo.pt/SAPO/Utility/Url/0.1/ http://js.sapo.pt/SAPO/Utility/Serialize/0.1/ http://js.sapo.pt/SAPO/Utility/String/0.1/ http://js.sapo.pt/SAPO/Communication/Syndication/0.1/ http://js.sapo.pt/SAPO/Communication/JsonP/0.1/ http://js.sapo.pt/SAPO/Communication/Ajax/2.1/ > bundle-remote-min.js


If like gz: 

    ./minifyJs... |gzip > bundle-sapo-min.js.gz


---

Any question
stvkoch@gmail.com
