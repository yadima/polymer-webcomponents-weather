http-server: npm install -g http-server

api key: 50e418e0f0c0e501713115a1df9ca42e
ajax for weather card: http://api.openweathermap.org/data/2.5/weather?q=Kiev&units=metric&APPID=50e418e0f0c0e501713115a1df9ca42e
ajax for weather list: http://api.openweathermap.org/data/2.5/forecast/daily?q=Kyiv&mode=json&units=metric&cnt=10&APPID=50e418e0f0c0e501713115a1df9ca42e
ajax for weather grid: http://api.openweathermap.org/data/2.5/history/city?q=Kyiv&mode=json&units=metric&type=day&start=' + start + '&end=' + end + '&APPID=50e418e0f0c0e501713115a1df9ca42e

Weather-card styling:

#card {
                margin: 15px;
                background-color: #fff;
                box-shadow: 0 2px 5px 0 rgba(0, 0, 0, 0.26);
                border-radius: 2px;
                padding: 8px;
                overflow: hidden;
            }

            #card>div {
                padding: 2px;
            }
            .large {
                font-size: x-large;
                color: #878787;
            }
            .medium {
                font-size: medium;
                color: #878787;
            }
            .degrees {
                float:left;
            }
            .degrees>span {
                font-size: 64px;
            }
            .celcius {
                float:left;
                margin-top: 8px;
                color: #878787;
            }
            #card.hide {
                display: none;
            }
            #card.dayData div {
                float: left;
            }