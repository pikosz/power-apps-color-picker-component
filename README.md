# Power Apps color picker component

###### Power Apps dynamic color picker component

#
#
### Overview
![](https://s7.gifyu.com/images/color-picker2.gif)
#
#
## How to use
###### 1. Download MSAPP file from this repository
######  2. Import MSAPP file into your application as below
![](https://s4.gifyu.com/images/import-cmp.png)
######  3. Add component to your application as below
![](https://s7.gifyu.com/images/color-picker-how-to-add.gif)
######  4. Define colors for users to pick in below format (Id field will be helpful if you want to store selected color value in database)
![](https://s4.gifyu.com/images/color-picker-colors-table.png)
######  5. In SelectedId property of component provide variable where you will store selected color id.
![](https://s7.gifyu.com/images/color-picker-selected-id.png)
######  6. In OnChange event of component provide code to update your variable to store selected color. There you can access Id and Color variables which will store selected color and id. (In case you are deselecting already selected color, Blank() values will be provided)
![](https://s4.gifyu.com/images/color-picker-onchange.png)
#
#
### Limitations
###### 1. Since WrapCount property of Gallery control has number of columns limitation, you can have up to 10 colors per single line. 
#
#
### Need help?
If you need help wit the application or want to contribute please contact me via [LinkedIn](https://www.linkedin.com/in/marek-pikosz/).

### License
MIT
