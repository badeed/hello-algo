<!--
    File: max_product_cutting.md
    Created Time: 2024-01-05
    Author: Krahets (krahets@163.com)
--->

<!-- [file]{max_product_cutting}-[class]{}-[func]{max_product_cutting} -->
https://pythontutor.com/render.html#code=import%20math%0A%0Adef%20max_product_cutting%28n%3A%20int%29%20-%3E%20int%3A%0A%20%20%20%20%22%22%22%E6%9C%80%E5%A4%A7%E5%88%87%E5%88%86%E4%B9%98%E7%A7%AF%EF%BC%9A%E8%B4%AA%E5%BF%83%22%22%22%0A%20%20%20%20%23%20%E5%BD%93%20n%20%3C%3D%203%20%E6%97%B6%EF%BC%8C%E5%BF%85%E9%A1%BB%E5%88%87%E5%88%86%E5%87%BA%E4%B8%80%E4%B8%AA%201%0A%20%20%20%20if%20n%20%3C%3D%203%3A%0A%20%20%20%20%20%20%20%20return%201%20*%20%28n%20-%201%29%0A%20%20%20%20%23%20%E8%B4%AA%E5%BF%83%E5%9C%B0%E5%88%87%E5%88%86%E5%87%BA%203%20%EF%BC%8Ca%20%E4%B8%BA%203%20%E7%9A%84%E4%B8%AA%E6%95%B0%EF%BC%8Cb%20%E4%B8%BA%E4%BD%99%E6%95%B0%0A%20%20%20%20a,%20b%20%3D%20n%20//%203,%20n%20%25%203%0A%20%20%20%20if%20b%20%3D%3D%201%3A%0A%20%20%20%20%20%20%20%20%23%20%E5%BD%93%E4%BD%99%E6%95%B0%E4%B8%BA%201%20%E6%97%B6%EF%BC%8C%E5%B0%86%E4%B8%80%E5%AF%B9%201%20*%203%20%E8%BD%AC%E5%8C%96%E4%B8%BA%202%20*%202%0A%20%20%20%20%20%20%20%20return%20int%28math.pow%283,%20a%20-%201%29%29%20*%202%20*%202%0A%20%20%20%20if%20b%20%3D%3D%202%3A%0A%20%20%20%20%20%20%20%20%23%20%E5%BD%93%E4%BD%99%E6%95%B0%E4%B8%BA%202%20%E6%97%B6%EF%BC%8C%E4%B8%8D%E5%81%9A%E5%A4%84%E7%90%86%0A%20%20%20%20%20%20%20%20return%20int%28math.pow%283,%20a%29%29%20*%202%0A%20%20%20%20%23%20%E5%BD%93%E4%BD%99%E6%95%B0%E4%B8%BA%200%20%E6%97%B6%EF%BC%8C%E4%B8%8D%E5%81%9A%E5%A4%84%E7%90%86%0A%20%20%20%20return%20int%28math.pow%283,%20a%29%29%0A%0A%22%22%22Driver%20Code%22%22%22%0Aif%20__name__%20%3D%3D%20%22__main__%22%3A%0A%20%20%20%20n%20%3D%2058%0A%0A%20%20%20%20%23%20%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95%0A%20%20%20%20res%20%3D%20max_product_cutting%28n%29%0A%20%20%20%20print%28f%22%E6%9C%80%E5%A4%A7%E5%88%87%E5%88%86%E4%B9%98%E7%A7%AF%E4%B8%BA%20%7Bres%7D%22%29&cumulative=false&curInstr=5&heapPrimitives=nevernest&mode=display&origin=opt-frontend.js&py=311&rawInputLstJSON=%5B%5D&textReferences=false