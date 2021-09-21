# API_project

[![hackmd-github-sync-badge](https://hackmd.io/HYAfsbiARf-u3WX7vna5EQ/badge)](https://hackmd.io/HYAfsbiARf-u3WX7vna5EQ)

###### tags: `NCTU` `109-1` `Introduction to Programming` `API` `Web Crawler`  

* Project Description:  
The project aims to help students in NCTU who live in Taipei backing home by bus. With many companies running bus services between Hsinchu and Taipei, students usually cannot decide which bus should they take. With the project, I hope to provide a one-stop service that can not only check ticket types and fares, but also estimate the time for users to get from the dormitory to the bus stop, whether by riding a bicycle or walking. 
* Core Techneches :  
It combines two API services and one web crawler application:  
    * [GOOGLE Distance Matrix API](https://developers.google.com/maps/documentation/distance-matrix/overview) for estimated journey time from their dorm to the bus stop.
    * [Public Transport Data eXchange(PTX)](https://ptx.transportdata.tw/PTX/) for real time bus information / Youbike rental status. 
    * [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) as a web crawler for bus fares and ticket prices.
* Setting before execution:
    ```python=12
    PTX_app_id = "PTX_API_ID"
    PTX_app_key = "PTX_API_KEY"
    GOOGLE_api_key = "GOOGLE_API_KEY"
    ```
    * For *PTX_app_id* and *PTX_app_key*, check [here](https://docs.google.com/viewer?url=https://github.com/ptxmotc/PTXWebTest/blob/master/member/PTX%E5%B9%B3%E8%87%BA%E5%B0%8E%E5%85%A5API%E6%A9%9F%E5%88%B6%E5%8F%8A%E6%9C%83%E5%93%A1%E7%94%B3%E8%AB%8B%E6%B5%81%E7%A8%8B%E8%AA%AA%E6%98%8E_V3.pdf?raw=true) for API service application.
    * For *GOOGLE_api_key*, check [here](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi-j8XVzY_zAhWeyosBHV3LDX0QFnoECBMQAQ&url=https%3A%2F%2Fconsole.developers.google.com%2Fapis&usg=AOvVaw2K_2CuoYrAwiReqstgD2X4) for API service application.
    
