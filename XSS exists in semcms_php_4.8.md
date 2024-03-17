**XSS exists in semcms_php_4.8**

1. In the Friendly Links column, clicking a friendly link will trigger the XSS code, indicating that the jump link contains XSS code.

![Snipaste_2024-03-17_10-27-58](https://github.com/gris2017/gris/blob/main/Snipaste_2024-03-17_10-27-58.jpg)

![image-20240317102455067](https://github.com/gris2017/gris/blob/main/image-20240317102455067.png)

![image-20240317102906300](https://github.com/gris2017/gris/blob/main/image-20240317102906300.png)



2. XSS code can exist directly in the background in the Follow US column, and XSS vulnerabilities can be triggered by refreshing the page.

![image-20240317102604848](https://github.com/gris2017/gris/blob/main/image-20240317102604848.png)

![image-20240317102626371](https://github.com/gris2017/gris/blob/main/image-20240317102626371.png)

![image-20240317102708851](https://github.com/gris2017/gris/blob/main/image-20240317102708851.png)



3. In product category management, XSS code exists in the category name column and can be displayed directly on the homepage.

![image-20240317102525564](https://github.com/gris2017/gris/blob/main/image-20240317102525564.png)

![image-20240317102936563](https://github.com/gris2017/gris/blob/main/image-20240317102936563.png)



4. In information management, there is also xss code in the information title column, which can also be displayed directly on the homepage.

![image-20240317103257885](https://github.com/gris2017/gris/blob/main/image-20240317103257885.png)

![image-20240317103110044](https://github.com/gris2017/gris/blob/main/image-20240317103110044.png)
