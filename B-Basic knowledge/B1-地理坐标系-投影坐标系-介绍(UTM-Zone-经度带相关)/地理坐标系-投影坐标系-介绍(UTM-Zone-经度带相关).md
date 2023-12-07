

# 【重要】地理坐标系与投影坐标系-1

> 【ArcGIS基础教学-坐标系-哔哩哔哩】 https://b23.tv/LRHdGSG



![lADPJxDj4umZZ_DNBDjNCWA_2400_1080](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/lADPJxDj4umZZ_DNBDjNCWA_2400_1080.jpg)

## 一、大地测量学中的坐标系概念



![172b615e1ab742d061b454c36333c979](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/172b615e1ab742d061b454c36333c979.jpg)



![01cb954a26be024099d2cdf608d2b34a](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/01cb954a26be024099d2cdf608d2b34a.jpg)



![83515275c78fa99b4940c4a925358ea6](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/83515275c78fa99b4940c4a925358ea6.jpg)





## 二、坐标系





![cca4b61bed70d3f43e484448b6b519e7](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/cca4b61bed70d3f43e484448b6b519e7.jpg)





![154975eb7a619f46108518b3c81ac9af](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/154975eb7a619f46108518b3c81ac9af.jpg)

![d891bc2276d13044f247c42b4a071e31](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/d891bc2276d13044f247c42b4a071e31.jpg)



![096e9f2ab3e03d906e2d6eae37d6157b](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/096e9f2ab3e03d906e2d6eae37d6157b.jpg)

## 三、3度带、6度带



![ccfb5644902b32a2100157d36ce4226d](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/ccfb5644902b32a2100157d36ce4226d.jpg)

![c24f170a8af16e1e0dedca6273a89d23](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/c24f170a8af16e1e0dedca6273a89d23.jpg)



![67a28310f490216010453829ee281972](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/67a28310f490216010453829ee281972.jpg)





![3ce67a85e5654d26bd041b46e5e8649e](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/3ce67a85e5654d26bd041b46e5e8649e.jpg)

![88eb2755fe2d5ff3aaed6144b03ab9db](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/88eb2755fe2d5ff3aaed6144b03ab9db.jpg)



> ![b70f7ff766a5e94492f1278be64712ad](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/b70f7ff766a5e94492f1278be64712ad.jpg)













#  【重要】中央经线（Central Meridian）的含义



UTM（Universal Transverse Mercator）投影系统是一种地图投影方法，将地球表面分割成一系列6度经度宽的纵带。每一条纵带被称作一个UTM区，并且每个区都有一个中央经线（Central Meridian）。

中央经线是**每个UTM区的参考经线**，是该区的**纵向中心**。中央经线的作用是作为该UTM区的坐标基准。在UTM投影中，中央经线的**东坐标被定义为500,000米**，以确保该区域内的所有点在投影后都有正的东坐标值。这样的设计是为了避免使用负数坐标。

例如，在第33区，中央经线是15度E。这意味着，如果一个点位于第33区，其坐标将相对于15度E的经线来计算，而且该点的东坐标将是相对于500,000米（中央经线的东坐标）的。

简而言之，中央经线在UTM投影中起着基准线的作用，是每个UTM区坐标计算的起点。





## 关于 UTM投影 的  中央经线和经度带划分 可以给我一个资料链接吗



ChatGPT ：我无法直接浏览互联网或提供实时链接，但我可以建议你查找一些关键词或在特定网站上进行搜索。

你可以在以下网站上查找关于UTM投影的中央经线和经度带划分的信息：

1. **USGS（United States Geological Survey）**

   - 网站链接: [USGS](https://www.usgs.gov/)
   - 搜索关键词: UTM projection Central Meridian Zone

2. **Wikipedia**

   - 页面链接: [Universal Transverse Mercator coordinate system](https://en.wikipedia.org/wiki/Universal_Transverse_Mercator_coordinate_system)

   - 这个页面详细解释了UTM坐标系统的工作原理，包括中央经线和经度带的划分。

     > ![undefined](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/800px-Modified_UTM_Zones.png)
     >
     > Universal Transverse Mercator (UTM) Grid Zones 31N thru 37N differ from the standard 6° wide by 84° for the northern hemisphere, in part to accommodate the southern half of the Kingdom of Norway. For more on its history, see Clifford J. Mugnier's article on Grids & Datums of The Kingdom of Norway that appeared in the October 1999 issue of PE&RS http://www.asprs.org/a/resources/grids/10-99-norway.pdf

3. **ESRI（Environmental Systems Research Institute）**

   - 网站链接: [ESRI](https://www.esri.com/)
   - 搜索关键词: UTM projection Central Meridian Zone

4. **NOAA（National Oceanic and Atmospheric Administration）**

   - 网站链接: [NOAA](https://www.noaa.gov/)
   - 搜索关键词: UTM projection explanation

请记住，在使用这些资源时，确保引用和依赖准确和可靠的信息源。



## 问题：中央经线（Central Meridian）的西侧坐标是怎么定义的？



在UTM（Universal Transverse Mercator）投影中，每个区域（6度经度宽）都有一个**中央经线（Central Meridian）**。这个中央经线的坐标被设定为500,000米（假东ing）。这是为了保证在该投影区域中的任何点都会有一个正的东坐标值。

对于中央经线以西的区域，由于中央经线已经被赋予了500,000米的坐标值，所以这些区域的坐标值会相对较小，但仍然是正值。例如，如果一个点位于中央经线以西100,000米的位置，那么**这个点的东坐标将是400,000米（500,000米 - 100,000米）**。这就确保了UTM投影中所有的坐标值都是正的，从而避免了使用负坐标值，简化了地图的使用和导航。



## 示意图

![image-20231021151956523](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/image-20231021151956523.png)



![image-20231021152457284](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/image-20231021152457284.png)

> 广东肇庆大排：23.3400715653, 111.5960505914【49N】
>
> 江西德兴铜矿：28.9947834510, 117.7542933898,【50N】
>
> 

> https://gisgeography.com/utm-universal-transverse-mercator-projection/?utm_source=ReviveOldPost&utm_medium=social&utm_campaign=ReviveOldPost
>
> https://gisgeography.com/utm-universal-transverse-mercator-projection/?utm_source=ReviveOldPost&utm_medium=social&utm_campaign=ReviveOldPost
>
> ![image-20231103215129855](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/image-20231103215129855.png)





# 【重要】 自动驾驶领域坐标系介绍

> 参考 【星火计划2.0】：https://www.bilibili.com/video/BV1Ze4y167Q6/?spm_id_from=333.999.0.0

![eed3ae8be0019b050aa52b1b10a77e17](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/eed3ae8be0019b050aa52b1b10a77e17.png)

- 地理坐标系：WGS84；

- 东北天（ENU）局部坐标系：例如，    "CRS_name":"GCS_WGS_1984_UTM_Zone_50N",       // 坐标参考系名称

  > 笛卡尔直角坐标系定义：
  >
  > - 原点o：举例origin(x=572476.768943, y=3205292.03191)，原点的UTM坐标通常在某一局部区域可以设置为定值，或者使用系统上电RTK稳定定位后，随机选择一个WGS84的经纬度点；
  >
  > - x轴：与地理的正东方向对应，单位，米；中央经线的x值为500Km。
  >
  > - y轴：与地理的正北方向对应，单位，米；对于北半球赤道纬度为0，对应Y值为0；所以也叫东北天（ENU）坐标系。
  >   > 赤道上的点在北半球的 Y 值为 0 米。
  >   > 赤道上的点在南半球的 Y 值为 10,000,000 米。
  >   > 在 UTM（Universal Transverse Mercator）坐标系中，南半球的处理方式与北半球不同。在南半球，UTM 坐标系统为了避免负数的 Y 值，采用了一个偏移量。这个偏移量通常是 10,000,000 米（或者说 10,000 公里）。
  >   > 例如，如果在南半球的某个位置，它距离赤道向南 500,000 米（或 500 公里），那么这个位置的 Y 值将是 9,500,000 米（因为 10,000,000 米 - 500,000 米 = 9,500,000 米）。这种设计有效地避免了南半球的负数坐标，使整个 UTM 系统在全球范围内具有一致性。
  >
  > - z轴：海拔高度信息，水平面为0米；
  >
  > - 航向：表示车辆、waypoint、dubins_pose等含有位姿信息的航向统一定义为东偏北, 范围为[0,2pi)，单位，rad； 

- 车辆坐标系\车体坐标系：右前天（RFU）坐标系；







# 地理坐标系与投影坐标系-2

> https://www.bilibili.com/read/cv16776101/

坐标系（Coordinate System，ArcGIS栅格数据的属性域中也将其称为“空间参考（Spatial Reference）”）的概念为：在参照系中，为确定空间一点的位置，按规定方法选取的有次序的一组数据，这就叫做“坐标”。在某一问题中规定坐标的方法，就是该问题所用的坐标系。换言之，坐标系是我们用一个或多个“坐标值”来表达和确定空间位置的。没有坐标系，坐标值就无从谈起，也就无法描述空间位置。 

在常见的GIS软件（例如ArcGIS）中，我们遇到的坐标系一般有两种：

1）地理坐标系（Geographic Coordinate System）；

2）投影坐标系（Projected Coordinate System）。

地理坐标：就是用经纬度表示地面点位的球面坐标。地理坐标系进行地图投影后就变成了投影坐标系。地图投影（Map Projection）是按照一定的数学法则将地球椭球面上的经纬网转换到平面上，使地面点位的地理坐标（φ，λ）与地图上相应的点位的平面直角坐标（x，y）或平面极坐标（δ，ρ）间，建立起一一对应的函数关系，能够实现由地球椭球面向地图平面的科学转变。简单来说就是将三维坐标系的经纬度经过复杂的数学法则转换成可以在平面显示的二维坐标对。

1、地理坐标系与投影坐标系的联系
坐标系是数据或地图的属性，而投影是坐标系的属性。一个数据或一张地图一定有坐标系，而一个坐标系可以有投影也可以没投影。只有投影坐标系才有投影，地理坐标系是没有投影的。因此，一个数据或一张地图亦是可以有投影也可以没投影的。当然，非要较真，把具有地理坐标系的数据显示在平面地图上肯定也有一个投影的过程。地理坐标系经过投影后变成投影坐标系，投影坐标系因此由地理坐标系和投影组成，投影坐标系必然包括有一个地理坐标系。

概括来说：投影坐标系（单位为米）=地理坐标系（单位为度）+投影，数据或者地图必须要有地理坐标系，投影可有可无，每个投影坐标系都对应一个地理坐标系，地理坐标系经过投影后称为投影坐标系。如果数据要转换投影的话，首先要考虑将数据转换成相同的地理坐标系，这其中涉及到一种地理(坐标)变换，除了常见的坐标转换，我们还可以通过“创建自定义地理(坐标)变换”工具通过参数转换，我们口中说的“三参法”和“七参法”就是这里的（参数一般涉密，请谨慎获取和使用）。



ArcGIS 中“地理坐标系（GCS）”与“投影坐标系（PCS）”的联系
 为什么要进行投影﹖

地理坐标为球面坐标，单位为度，不方便进行距离、方位、面积等参数的量算（例如如何在地理坐标系表示的地 图中计算一块土地的面积？或者说如何用经纬度表达一块土地的面积？这是不能表示的，因为一度经度在不同的纬度表示的弧长是不一样的，在赤道附近弧长最长，在两极附近弧长最短）。投影显示效果符合视觉心理，并易于进行距离、方位、面积等量算和各种空间分析。再仔细看相同地区投影前后形状有所变化，当发生面积、角度、长度等的变化，称为形变。为什么会发生图的形变，那是因为地图投影解决由球面向平面的转换，并不能保持平面与球面之间长度（距离）、角度（形状）、面积等方面完全不变（地球是一个球面，而地图必须是一个平面展示的，因此将地球表面展开成地图平面必然会产生裂隙或褶皱（拉伸处理），必须采用一定的数学方法将曲面展成平面，而且使其变形较小）。至今还没有一种完美的地图投影能做到完全没有形变和误差，所以投影方法就和那句话说的一样：没有最好的，只有最适合的。

下面以一个具体示例来初识ArcGIS中的坐标系。“WGS_1984_UTM_Zone_50N” 是一个“投影坐标系（Projected Coordinate System）”。“WKID”是该坐标系的编号，“ESPG”是“European Petroleum Survey Group”的缩写，表示其由“欧洲石油调查组织”发布。可知，“WGS_1984_UTM_Zone_50N”这个投影坐标系由两部分组成：名为“Transverse_Mercator”的“投影（Projection）”和名为“GCS_WGS_1984”的“地理坐标系（GeographicCoordinate System）”。

WGS_1984_UTM_Zone_50N

WKID:32650 Authority: EPSG

Projection:Transverse_Mercator

False_Easting:500000.0

False_Northing:0.0

Central_Meridian:117.0

Scale_Factor:0.9996

Latitude_Of_Origin:0.0

LinearUnit: Meter (1.0)

GeographicCoordinate System: GCS_WGS_1984

AngularUnit: Degree (0.0174532925199433)

PrimeMeridian: Greenwich (0.0)

Datum: D_WGS_1984

Spheroid:WGS_1984

       Semimajor Axis: 6378137.0

Semiminor Axis: 6356752.314245179

Inverse Flattening:298.257223563

地理坐标系由三个参数来定义：角度单位（Angular Unit）、本初子午线（Prime Meridian）和大地测量系统（Datum）。地理坐标系“GCS_WGS_1984”使用的角度单位为“度（Degree）”，0.0174532925199433这个数字等于“π/180”，使用的本初子午线为0.0度经线，即格林威治皇家天文台（Greenwich）所在位置的经线，使用的大地测量系统则为“D_WGS_1984”。

地理坐标系的最重要的参数是“大地测量系统（Datum）”，而大地测量系统的最重要的参数是“椭球（Spheroid）”。椭球相同，大地测量系统不一定相同，因为原点（origin）和方位（orientation）可以不同。想象一下，同一个椭球，首先可以固定在三维空间中的任意一个点，并且在固定于某点后还能以三个自由度任意地旋转其方位（朝向）。当然，具体国家或地区在选择大地测量系统时，总是选择与这一国家或地区的地面最吻合的大地测量系统，而不是拍脑袋随便选的。我们拿到的境内的许多数据使用的都是“D_Xian_1980”大地测量系统，因为“D_Xian_1980”是我们依据我国疆域的地面自己定义出来的，因而较“D_WGS_1984”与我国疆域的地面更吻合。“D_WGS_1984”大地测量系统使用的椭球为“WGS_1984”，而“WGS_1984”椭球的“长半轴（Semimajor Axis）”和“短半轴（Semiminor Axis）”分别为6378137.0和6356752.314245179，其“反扁率（Inverse Flattening）”为298.257223563，等于Semimajor Axis/( Semimajor Axis - Semiminor Axis)。

投影的参数对不同的投影方法有一定差别，在此也不详述各投影的具体参数。投影坐标系“WGS_1984_UTM_Zone_50N”使用的“投影（Projection）”名为“横轴墨卡托（Transverse_Mercator）”，然而这个名称并不能完全准确概括其投影。事实上，投影坐标系“WGS_1984_UTM_Zone_50N”这个名称中的“WGS_1984”指出了其地理坐标系为“GCS_WGS_1984”，而“UTM_Zone_50N”则指出了其投影。“UTM_Zone_50N”这个名称指出，其投影方法是“通用横轴墨卡托（Universal Transverse Mercator，UTM）”，其投影带为北半球第50带，这个“Zone_50N”的“中央经线（Central Meridian）”正是117.0度，在“Transverse_Mercator”的参数中得到了体现。举一反三，“Xian_1980_GK_CM_117E”这个坐标系使用的地理坐标系为“GCS_Xian_1980”，而投影名称“GK_CM_117E”指出其使用以东经117度为中央经线的“高斯-克吕格（Gauss-Kruger，GK）”投影。投影的另一个重要参数是“东偏（False Easting）”。有些投影会在X坐标值前加上投影带号，比如：“Xian_1980_GK_Zone_20”的“false_easting”参数为20500000.0，其中20为投影带号，而“Xian_1980_GK_CM_117E”的“false_easting”参数为500000.0，尽管它们的中央经线都为东经117度（各投影的具体参数和相关算法能够系统学习地图学是最好的，如果想了解的话可以参照https://www.jianshu.com/p/6f3f00546f20）。

## 3度带和6度带

国际上通用最常见的地理坐标系是WGS84，但由于地区差异，我国有自己的地理坐标系，如CGCS2000、北京54、西安80等，虽然投影类型五花八门，但是我国基本比例尺地形图除1:100万采用兰勃特投影（Lambert）外，其他诸如1:1万、1:2.5万、1:5万、1:10万、1:25万、1:50万比例尺的地形图均采用高斯-克吕格投影，为减少投影变形，高斯-克吕格投影分为3度或6度带投影。地理坐标系根据需求可以选择，投影带如何选择关乎着数据的精度问题。不同投影带靠近中央经线的地区形变最小（中央子午线长度变形比为1），形变向中央经线两边随着距离的增大而越大。在同一条经线上，长度变形随纬度的降低而增大，在赤道处为最大;在同一条纬线上，长度变形随经差的增加而增大，且增大速度较快。

UTM投影带计算公式如下：

北半球地区，选择最后字母为“N”的带，南半球“S”

带号=（经度整数位/6）的整数部分+31


解决完国际通用之后解决国内特有：

①CGCS2000_3_Degree_GK_CM_105E

②CGCS2000_3_Degree_GK_Zone_35

③CGCS2000_GK_CM_105E

④CGCS2000_GK_Zone_18

①3°分带下的35带投影（横坐标没有带号）

②3°分带下的35带投影（横坐标有带号）

③6°分带下的18带投影（横坐标没有带号）

④6°分带下的18带投影（横坐标有带号）

一般，在我国标准地形图上，X坐标的前两位代表所在分度带带号，其余的表示X坐标，规定如此。

3度带带号=（经度+1.5°）/3取整

6度带带号=（经度+6°）/6取整


2、常用操作
2.1坐标系选择、新建与编辑
坐标系的其他操作都会涉及到选择、新建与编辑等，这些操作可在打开的数据或地图等的“Properties”窗口中的“坐标系”（Coordinate System）或“XY Coordinate System”标签中进行（图2）。注意无论我们是在内容列表中的数据框属性还是图层属性对话框中更改都只是修改显示的坐标系，不会修改源数据的坐标系，要想修改源数据的坐标系可以在目录列表右键数据属性，在shapefile属性对话框中修改数据的XY坐标系（或者在ArcCatalog中右键数据属性进行修改，ArcMap只是将这一功能集成在了目录列表），或者使用其他投影转换工具转换投影。用户可以从“Favorites”、“Geographic Coordinate System”、“ProjectedCoordinate System”和“Layers”等文件夹中选择坐标系，或使用“Import”导入其他数据的坐标系。“Layers”文件夹只有当ArcMap或ArcScene中的Layers加载有数据（Layer）时才会显示出来，而在ArcCatalog中操作则不会出现。另外，使用“Clear”可以清除数据或地图的坐标系。用户也可以根据需要新建坐标系，在新建投影坐标系的操作窗口中，用户需要设置投影坐标系的名称（Name）、投影（Projection）、单位（Linear Unit）和地理坐标系（Geographic CoordinateSystem）等参数。

ArcMap中还牵涉到一个动态投影的问题，这边一并讲一下。动态投影：数据的坐标系和ArcMap中的数据框（Data Frame）的坐标系不一致，数据就临时显示变换到数据框的坐标系。ArcMap的数据框的坐标系统默认为第一个加载到当前数据框数据的坐标系统一致，后加入的数据，如果和当前数据框坐标系统不同，则ArcMap会自动做动态投影变换，即把后加入的数据投影变换到当前坐标系统下显示，但此时数据文件所存储的实际数据坐标值并没有改变，只是显示形态上的变化，因此叫动态投影。表现这一点最明显的例子就是在数据导出时，用户可以选择是按数据源的坐标系统导出，还是按照当前数据框的坐标系统导出数据，数据的投影信息与数据框的投影信息有两个，不完全一致。

总之：数据有坐标系，数据框也有坐标系，新建一个文档后，数据框的默认的坐标系和第一个加载数据的坐标系一致，以后再加数据，数据框坐标系保持不变，除非你专门修改数据框的坐标系。当数据的坐标系和数据框坐标不一致，数据会动态投影到数据框上。

图2数据框坐标系选择、新建与编辑等操作的入

### 2.2坐标系定义

坐标系定义是指定义数据的属性坐标系。也即将与数据的真实坐标系相同的坐标系赋予给数据的属性。坐标系定义可以通过两种方式来实现：一是在Catalog里面访问该数据的属性对话框进行修改（定义）；二是使用ArcToolbox -> Projections and Transformations -> DefineProject工具（图3）。如果该数据已有属性坐标系，数据输入处会出现警告符号，警告用户已有属性坐标系将被覆盖（可以忽略此警告）。如果数据在ArcMap或ArcScene中打开（被锁定）后，那么就不能在Catalog中改变数据的坐标系了，但是仍然可以利用ArcToolbox中的Define Project工具来定义数据的坐标系，除非这一数据同时也在另外的ArcMap、ArcScene或ArcCatalog中被打开使用，这种被锁定或者占用的错误提示框在专业软件或者是其他软件中非常常见（例如我们要从电脑中删除某样东西时提示此文件已被某某占用），同样的错误也常出现在我们在对表的编辑中，同时在excel和ArcMap打开了表，会显示异常错误。

图3 使用ArcToolbox 中“Define Project”工具进行坐标系定义

### 2.3坐标系转换

坐标系转换是指转换数据的真实坐标系。坐标系转换的前提是数据的属性坐标系与数据的真实坐标系吻合。矢量数据的坐标系转换通过ArcToolbox -> Projections and Transformations -> Project工具来实现（图4），栅格数据的坐标系转换通过ArcToolbox -> Projectionsand Transformations -> Raster -> Project Raster工具来实现。（注：不同ArcGIS版本工具在ArcToolbox中的位置可能略有不同，此处为ArcGIS 10.8中的路径）。

使用 “Project”工具进行矢量数据的坐标系转换

使用 “Project Raster”工具进行栅格数据的坐标系转换
在选择好输入数据，并定义好输出数据及其坐标系后，用户有可能被要求定义“Geographic Transformation”。这个“Geographic Transformation”被用于两个不同地理坐标系（大地测量系统）之间的转换。只有当输入坐标系和输出坐标系拥有不同的大地测量系统时，这个输入才被要求。在某些情况下，系统会从已有的“Geographic Transformation”中根据输入和输出坐标系自动选择出合理的“Geographic Transformation”，而某些情况下则需要用户从已有的“Geographic Transformation”中进行选择。

坐标系转换理论上可以在任意两个覆盖了数据范围的坐标系之间进行。坐标系转换可以在地理坐标系与投影坐标系之间，可以在地理坐标系与地理坐标系之间，也可以在投影坐标系与投影坐标系之间。

坐标系转换包括了两种过程：

1）大地测量系统（地理坐标系）转换；

2）投影（或反投影）。

例如，将地理坐标系“GCS_WGS_1984”转换为投影坐标系“Xian_1980_GK_CM_117E”包括了两个过程：分别是一个将大地测量系统“D_WGS_1984”转换为大地测量系统“D_Xian_1980”的过程和一个将地理坐标系“GCS_Xian_1980”投影为投影坐标系“Xian_1980_GK_CM_117E”的过程。再例如，将投影坐标系“WGS_1984_Web_Mercator”转换为投影坐标系“WGS_1984_UTM_Zone_50N”包括了三个过程：分别是一个将投影坐标系“WGS_1984_Web_Mercator”转为地理坐标系“GCS_WGS_1984_Major_Auxiliary_Sphere”的过程（反投影），一个将大地测量系统“D_WGS_1984_Major_Auxiliary_Sphere”转换为大地测量系统“GCS_WGS_1984”的过程和一个将地理坐标系“GCS_WGS_1984”投影为投影坐标系“WGS_1984_UTM_Zone_50N”的过程。

栅格数据的坐标系转换与矢量数据的坐标系转换的一个重要不同是：栅格数据的坐标系转换需要设置栅格分辨率。如果是投影坐标系之间或地理坐标系之间的转换，系统一般会默认分辨率数值不变，如果是地理坐标系与投影坐标系之间的转换，系统会自动估计出一个合理的分辨率数值。

### 2.4坐标系猜测

坐标系猜测是指猜测数据的真实坐标系，并且把数据的属性坐标系设置为真实坐标系。这在不知道数据的坐标系或数据的属性坐标系是错误的时候是需要的。比如，给你若干点的坐标值，但是不告诉你这些坐标值是在什么坐标系下的坐标值。在这种情况下，最好的方式是向数据的提供方询问数据的真实坐标系是什么。如果不得不猜测数据的真实坐标系，其基本原理是根据数据的坐标值特征来猜测。经验将会很重要。如果数据的坐标值看起来像是经纬度数值，那么认为其真实坐标系为地理坐标系“GCS_WGS_1984”将不会带来很大误差。如果数据的坐标值是地面长度（通常数值很大），那么可以基本认为其真实坐标系为投影坐标系。如果知道该数据大概的空间范围，可以找出该空间范围内的坐标系正确的任一“参考数据”，将其与属性坐标系未知的“目标数据”加载于同一地图中，并将地图坐标系设置为你怀疑的投影坐标系。当目标数据与参考数据范围吻合时，可以猜测此怀疑的投影坐标系即为目标数据的真实坐标系，并可辅以其他手段进行验证。怀疑的投影坐标系可以有很多个，选择哪些投影坐标系作为怀疑对象，需要基于经验根据数据的坐标值特征进行判断。比如，加投影带号与不加投影带号的投影坐标系中的数据X坐标值的大小在很多时候是有明显差异的。

在数据分析之前，进行以下有关坐标系的准备工作是一个良好的习惯：保证所有数据的坐标系都是正确的，也即使所有数据的属性坐标系都与其真实坐标系吻合，统一所有数据的坐标系，利用坐标系转换实现。并且，这种统一的坐标系一般宜为投影坐标系，因为只有在投影坐标系下才能正确地进行距离、长度、面积、坡度等度量的计算。当然，有时我们做大尺度的工作，比如进行全球尺度的显示或分析时，一般就用地理坐标系，不用投影坐标系。

投稿主体参照以下两篇文章并结合了我自己的一些想法

https://mp.weixin.qq.com/s/jnY-OWFtR4SsdqQKnLoFoA

https://mp.weixin.qq.com/s/q7qV60IRuPqW-qbYxkY8zQ

如果想实践操作或者是学习投影转换例子可以参考：

https://zhuanlan.zhihu.com/p/34932577 作者：小爽要瘦瘦 https://www.bilibili.com/read/cv16776101/ 出处：bilibili

## 国内常用坐标系

1. WGS84(EPSG:4326) : 目前最流行的地理坐标系统，美国GPS就是使用的这个。一般的国外地图如谷歌地图、OpenStreetMap（OSM）均采用WGS84。
2. Pseudo-Mercator(EPSG:3857) : 投影坐标系。伪墨卡托投影，也称为球体墨卡托，Web Mercator。它是基于墨卡托投影的，把 WGS84 投影到正方形。各大互联网地图公司以它为准。伪墨卡托非常适合显示数据、但不适合存储数据。一般用 WGS84 存储数据、用伪墨卡托显示数据。
3. CGCS2000(4490) : 国家大地坐标系，类似于WGS84，是原始坐标系，与WGS84相近，除厘米级的高精应用外，一般可将WGS84和CGCS2000视为一样。国家背书的天地图采用CGCS2000。
4. xian80(4610) : 1980年西安坐标系，又简称西安大地原点，二维坐标，现已退出历史舞台。2018年12月14日，自然资源部宣布自2019年1月1日起，全面停止向社会提供1954年北京坐标系和1980西安坐标系基础测绘成果。
5. beijing54(4214) : 北京54坐标系(BJZ54)，二维坐标，现已退出历史舞台。2018年12月14日，自然资源部宣布自2019年1月1日起，全面停止向社会提供1954年北京坐标系和1980西安坐标系基础测绘成果。
6. GCJ02，又称火星坐标系，是我国测绘局（国测局，GCJ）制定的坐标系，由WGS84坐标系加密而成。一般的国内企业地图服务如高德地图、腾讯地图均采用GCJ02。
7. BD09，即百度坐标系，是百度地图在GCJ02的基础上进行二次加密后得到的坐标系。







# 8. 坐标参考系[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#coordinate-reference-systems)

> https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html

 

目标：了解坐标参考系。

关键词：坐标参考系(CRS)，地图投影，动态投影，纬度，经度，北距，东距

## 8.1. 概述[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#overview)

**Map projections** 试着在一张纸或电脑屏幕上描绘地球表面或地球的一部分。用外行人的话说，地图投影试图将地球从球形(3D)转变为平面(2D)。

A **coordinate reference system** (CRS)然后定义您的地理信息系统中的二维投影地图如何与地球上的真实位置相关。决定使用哪种地图投影和CRS取决于您要处理的区域的区域范围、您要进行的分析，而且通常还取决于数据的可用性。

## 8.2. 详细的地图投影

> https://zhuanlan.zhihu.com/p/523023493

表示地球形状的一种传统方法是使用地球仪。然而，这种方法存在一个问题。尽管地球仪保留了地球的大部分形状，并展示了大陆大小的特征的空间形状，但它们很难放在口袋里。它们也只能在极小的比例(例如1：1亿)下方便地使用。

在地理信息系统中常用的专题地图数据大多具有相当大的比例尺。典型的地理信息系统数据集具有1：25万或更大的比例，具体取决于细节级别。这种大小的地球仪制造起来既困难又昂贵，而且更难随身携带。因此，制图员开发了一套名为 **map projections** 旨在以合理的精确度显示二维的球形地球。

近距离观察时，地球似乎相对平坦。然而，当我们从太空中观察时，我们可以看到地球是相对球形的。正如我们将在接下来的地图制作主题中看到的那样，地图是现实的表现。它们不仅被设计成代表特征，而且还代表了它们的形状和空间安排。每个地图投影都有 **advantages** 和 **disadvantages** 。地图的最佳投影取决于 **scale** 地图，以及它将被用于的目的。例如，如果用于绘制整个非洲大陆的地图，投影可能具有不可接受的扭曲，但可能是一个很好的选择 **large-scale (detailed) map** 你的国家。地图投影的属性也可能影响地图的某些设计特征。有些投影适用于小区域，有些适用于绘制东西向范围较大的区域，有些则更适合绘制南北范围较大的区域。

## 8.3. 地图投影的三个家族[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#the-three-families-of-map-projections)

The process of creating map projections is best illustrated by positioning a light source inside a transparent globe on which opaque earth features are placed. Then project the feature outlines onto a two-dimensional flat piece of paper. Different ways of projecting can be produced by surrounding the globe in a **cylindrical** fashion, as a **cone**, or even as a **flat surface**. Each of these methods produces what is called a **map projection family**. Therefore, there is a family of **planar projections**, a family of **cylindrical projections**, and another called **conical projections** (see [图 8.16](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-projection-families))

[![../../_images/projection_families.png](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/projection_families.png)](https://www.osgeo.cn/qgisdoc/_images/projection_families.png)

图 8.16 *地图投影的三个家族。它们可以由a)柱面投影、b)圆锥投影或c)平面投影来表示。*[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#id1)

当然，今天，将球形地球投影到一张平板纸上的过程是利用几何和三角的数学原理完成的。这重建了光在地球上的物理投影。



![img](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/utm_zones.png)

## 8.4. 地图投影的准确性[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#accuracy-of-map-projections)

Map projections are never absolutely accurate representations of the spherical earth. As a result of the map projection process, every map shows **distortions of angular conformity, distance and area**. A map projection may combine several of these characteristics, or may be a compromise that distorts all the properties of area, distance and angular conformity, within some acceptable limit. Examples of compromise projections are the **Winkel Tripel projection** and the **Robinson projection** (see [图 8.17](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-robinson-projection)), which are often used for producing and visualizing world maps.

[![../../_images/robinson_projection.png](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/robinson_projection.png)](https://www.osgeo.cn/qgisdoc/_images/robinson_projection.png)

图 8.17 *罗宾逊投影是一种折衷方案，其中面积、角度一致性和距离的扭曲都是可以接受的。*[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#id2)

通常不可能在地图投影中同时保留所有特征。这意味着当您想要执行准确的分析操作时，您需要使用为您的分析提供最佳特征的地图投影。例如，如果需要在地图上测量距离，则应尝试对数据使用可提供高精度距离的地图投影。

### 8.4.1. 角度一致的地图投影[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#map-projections-with-angular-conformity)

使用地球仪时，指南针的主要方向(北、东、南、西)将始终彼此成90度角。换句话说，东面总是与北面成90度角。保持正确 **angular properties** 也可以保存在地图投影上。保留角度一致性这一属性的地图投影称为 **conformal** 或 **orthomorphic projection** 。

These projections are used when the **preservation of angular relationships** is important. They are commonly used for navigational or meteorological tasks. It is important to remember that maintaining true angles on a map is difficult for large areas and should be attempted only for small portions of the earth. The conformal type of projection results in distortions of areas, meaning that if area measurements are made on the map, they will be incorrect. The larger the area the less accurate the area measurements will be. Examples are the **Mercator projection** (as shown in [图 8.18](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-mercator-projection)) and the **Lambert Conformal Conic projection**. The U.S. Geological Survey uses a conformal projection for many of its topographic maps.

[![../../_images/mercator_projection.png](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/mercator_projection.png)](https://www.osgeo.cn/qgisdoc/_images/mercator_projection.png)

图 8.18 *例如，墨卡托投影用于角度关系很重要，但面积关系扭曲的地方。*[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#id3)

### 8.4.2. 等距离地图投影[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#map-projections-with-equal-distance)

If your goal in projecting a map is to accurately measure distances, you should select a projection that is designed to preserve distances well. Such projections, called **equidistant projections**, require that the **scale** of the map is **kept constant**. A map is equidistant when it correctly represents distances from the centre of the projection to any other place on the map. **Equidistant projections** maintain accurate distances from the centre of the projection or along given lines. These projections are used for radio and seismic mapping, and for navigation. The **Plate Carree Equidistant Cylindrical** (see [图 8.19](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-plate-caree-projection)) and the **Equirectangular projection** are two good examples of equidistant projections. The **Azimuthal Equidistant projection** is the projection used for the emblem of the United Nations (see [图 8.20](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-azimuthal-equidistant-projection)).

[![../../_images/plate_carree_projection.png](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/plate_carree_projection.png)](https://www.osgeo.cn/qgisdoc/_images/plate_carree_projection.png)

图 8.19 *例如，当精确的距离测量很重要时，就使用托盘等距柱面投影。*[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#id4)

[![../../_images/azimuthal_equidistant_projection.png](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/azimuthal_equidistant_projection.png)](https://www.osgeo.cn/qgisdoc/_images/azimuthal_equidistant_projection.png)

图 8.20 *联合国徽标使用方位等距投影。*[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#id5)

### 8.4.3. 面积相等的投影[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#projections-with-equal-areas)

When a map portrays areas over the entire map, so that all mapped areas have the same proportional relationship to the areas on the Earth that they represent, the map is an **equal area map**. In practice, general reference and educational maps most often require the use of **equal area projections**. As the name implies, these maps are best used when calculations of area are the dominant calculations you will perform. If, for example, you are trying to analyse a particular area in your town to find out whether it is large enough for a new shopping mall, equal area projections are the best choice. On the one hand, the larger the area you are analysing, the more precise your area measures will be, if you use an equal area projection rather than another type. On the other hand, an equal area projection results in **distortions of angular conformity** when dealing with large areas. Small areas will be far less prone to having their angles distorted when you use an equal area projection. **Alber's equal area**, **Lambert's equal area** and **Mollweide Equal Area Cylindrical projections** (shown in [图 8.21](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-mollweide-equal-area-projection)) are types of equal area projections that are often encountered in GIS work.

[![../../_images/mollweide_equal_area_projection.png](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/mollweide_equal_area_projection.png)](https://www.osgeo.cn/qgisdoc/_images/mollweide_equal_area_projection.png)

图 8.21 *例如，Mollweide等面积圆柱形投影确保所有贴图区域与地球上的区域具有相同的比例关系。*[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#id6)

请记住，地图投影是一个非常复杂的主题。全世界有数百种不同的投影，每一种都试图在一张扁平的纸上尽可能忠实地描绘地球表面的某一部分。在现实中，选择使用哪种投影通常会为您做出选择。大多数国家都有常用的预测，当数据交换时，人们会遵循 **national trend** 。

## 8.5. 详细介绍坐标系(CRS)[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#coordinate-reference-system-crs-in-detail)

在坐标参考系(CRS)的帮助下，地球上的每个地方都可以用一组三个数字来指定，称为坐标。一般说来，CRS可以分为 **projected coordinate reference systems** (也称为笛卡尔或直角坐标系)和 **geographic coordinate reference systems** 。

### 8.5.1. 地理坐标系[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#geographic-coordinate-systems)

地理坐标参考系的使用非常普遍。它们使用纬度和经度，有时还使用高度值来描述地球表面的位置。最受欢迎的是叫 **WGS 84** 。

**Lines of latitude** run parallel to the equator and divide the earth into 180 equally spaced sections from North to South (or South to North). The reference line for latitude is the equator and each **hemisphere** is divided into ninety sections, each representing one degree of latitude. In the northern hemisphere, degrees of latitude are measured from zero at the equator to ninety at the north pole. In the southern hemisphere, degrees of latitude are measured from zero at the equator to ninety degrees at the south pole. To simplify the digitisation of maps, degrees of latitude in the southern hemisphere are often assigned negative values (0 to -90°). Wherever you are on the earth’s surface, the distance between the lines of latitude is the same (60 nautical miles). See [图 8.22](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-geographic-crs) for a pictorial view.

[![../../_images/geographic_crs.png](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/geographic_crs.png)](https://www.osgeo.cn/qgisdoc/_images/geographic_crs.png)

图 8.22 *地理坐标系，其纬线平行于赤道，经线以本初子午线穿过格林威治。*[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#id7)

**Lines of longitude**, on the other hand, do not stand up so well to the standard of uniformity. Lines of longitude run perpendicular to the equator and converge at the poles. The reference line for longitude (the prime meridian) runs from the North pole to the South pole through Greenwich, England. Subsequent lines of longitude are measured from zero to 180 degrees East or West of the prime meridian. Note that values West of the prime meridian are assigned negative values for use in digital mapping applications. See [图 8.22](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-geographic-crs) for a pictorial view.

在赤道，并且只在赤道，一条经线表示的距离等于由一度纬度表示的距离。随着你向两极移动，经线之间的距离逐渐变小，直到在电线杆的确切位置，所有360度的经度由一个你可以把手指放在上面的点表示(尽管你可能想戴上手套)。使用地理坐标系，我们有一个线网，将地球分成几个正方形，在赤道处覆盖大约12363.365平方公里-这是一个很好的开始，但对于确定正方形内任何东西的位置来说，用处不是很大。

To be truly useful, a map grid must be divided into small enough sections so that they can be used to describe (with an acceptable level of accuracy) the location of a point on the map. To accomplish this, degrees are divided into **minutes** (`'`) and **seconds** (`"`). There are sixty minutes in a degree, and sixty seconds in a minute (3600 seconds in a degree). So, at the equator, one second of latitude or longitude = 30.87624 meters.

### 8.5.2. 投影坐标参考系[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#projected-coordinate-reference-systems)

A two-dimensional coordinate reference system is commonly defined by two axes. At right angles to each other, they form a so called **XY-plane** (see [图 8.23](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-projected-crs) on the left side). The horizontal axis is normally labelled **X**, and the vertical axis is normally labelled **Y**. In a three-dimensional coordinate reference system, another axis, normally labelled **Z**, is added. It is also at right angles to the **X** and **Y** axes. The **Z** axis provides the third dimension of space (see [图 8.23](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-projected-crs) on the right side). Every point that is expressed in spherical coordinates can be expressed as an **X Y Z** coordinate.

[![../../_images/projected_crs.png](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/projected_crs.png)](https://www.osgeo.cn/qgisdoc/_images/projected_crs.png)

图 8.23 *二维和三维坐标参考系。*[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#id8)

南半球(赤道以南)的投影坐标参考系通常以赤道上的特定位置为原点 **Longitude** 。这意味着Y值向南增加，X值向西增加。在北半球(赤道以北)，原点也是赤道在一个特定的位置 **Longitude** 。然而，现在Y值向北增加，X值向东增加。在接下来的部分中，我们将描述一种投影坐标参考系，称为通用横坐标墨卡托(UTM)，通常用于南非。



## 8.6. 万能横向墨卡托(UTM)CRS详细介绍[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#universal-transverse-mercator-utm-crs-in-detail)

The Universal Transverse Mercator (UTM) coordinate reference system has its origin on the **equator** at a specific **Longitude**. Now the Y-values increase southwards and the X-values increase to the West. The UTM CRS is a global map projection. This means, it is generally used all over the world. But as already described in the section 'accuracy of map projections' above, the larger the area (for example South Africa) the more distortion of angular conformity, distance and area occur. To avoid too much distortion, the world is divided into **60 equal zones** that are all **6 degrees** wide in longitude from East to West. The **UTM zones** are numbered **1 to 60**, starting at the **antimeridian** (**zone 1** at 180 degrees West longitude) and progressing East back to the **antemeridian** (**zone 60** at 180 degrees East longitude) as shown in [图 8.24](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-utm-zones).

[![../../_images/utm_zones.png](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/utm_zones-1699107236376-19.png)](https://www.osgeo.cn/qgisdoc/_images/utm_zones.png)

图 8.24 *宇宙横向墨卡托地带。对于南非，使用UTM区域33S、34S、35S和36S。*[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#id9)

As you can see in [图 8.24](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-utm-zones) and [图 8.25](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-utm-for-sa), South Africa is covered by four **UTM zones** to minimize distortion. The **zones** are called **UTM 33S**, **UTM 34S**, **UTM 35S** and **UTM 36S**. The **S** after the zone means that the UTM zones are located **south of the equator**.

[![../../_images/utm_for_sa.png](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/utm_for_sa.png)](https://www.osgeo.cn/qgisdoc/_images/utm_for_sa.png)

图 8.25 *UTM带33S、34S、35S和36S及其中央经度(子午线)用于高精度地预测南非。红十字会显示了一个感兴趣的区域(Aoi)。*[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#id10)

Say, for example, that we want to define a two-dimensional coordinate within the **Area of Interest (AOI)** marked with a red cross in [图 8.25](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-utm-for-sa). You can see, that the area is located within the **UTM zone 35S**. This means, to minimize distortion and to get accurate analysis results, we should use **UTM zone 35S** as the coordinate reference system.

The position of a coordinate in UTM south of the equator must be indicated with the **zone number** (35) and with its **northing (Y) value** and **easting (X) value** in meters. The **northing value** is the distance of the position from the **equator** in meters. The **easting value** is the distance from the **central meridian** (longitude) of the used UTM zone. For UTM zone 35S it is **27 degrees** **East** as shown in [图 8.25](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-utm-for-sa). Furthermore, because we are south of the equator and negative values are not allowed in the UTM coordinate reference system, we have to add a so called **false northing value** of 10,000,000 m to the northing (Y) value and a false easting value of 500,000 m to the easting (X) value. This sounds difficult, so, we will do an example that shows you how to find the correct **UTM 35S** coordinate for the **Area of Interest**.

### 8.6.1. 北距(Y)值[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#the-northing-y-value)

我们要查找的位置是赤道以南3,550,000米，因此北距(Y)值得到一个 **negative sign** 和-3,550,000米。根据UTM的定义，我们必须添加一个 **false northing value** 这意味着我们坐标的北距(Y)值是6,450,000米(-3,550,000米+10,000,000米)。

### 8.6.2. 东距(X)值[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#the-easting-x-value)

First we have to find the **central meridian** (longitude) for the **UTM zone 35S**. As we can see in [图 8.25](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#figure-utm-for-sa) it is **27 degrees East**. The place we are looking for is **85,000 meters West** from the central meridian. Just like the northing value, the easting (X) value gets a negative sign, giving a result of **-85,000 m**. According to the UTM definitions we have to add a **false easting value** of 500,000 m. This means the easting (X) value of our coordinate is 415,000 m (-85,000 m + 500,000 m). Finally, we have to add the **zone number** to the easting value to get the correct value.

因此，我们的坐标 **Point of Interest** ，投影于 **UTM zone 35S** 将写成： **35 415,000 m E / 6,450,000 m N** 。在某些GIS中，如果定义了正确的UTM带35S并在系统内将单位设置为米，则坐标也可能简单地显示为 **415,000 6,450,000** 。

## 8.7. 即时投影[](https://www.osgeo.cn/qgisdoc/docs/gentle_gis_introduction/coordinate_reference_systems.html#on-the-fly-projection)

正如您可能想象的那样，可能会出现这样一种情况，即要在GIS中使用的数据投影到不同的坐标参考系中。例如，您可能会获得一个显示以UTM 35S投影的南非边界的矢量图层，以及另一个包含地理坐标系WGS 84中提供的有关降雨的点信息的矢量图层。在地理信息系统中，这两个矢量层被放置在地图窗口的完全不同的区域，因为它们具有不同的投影。

为解决此问题，许多GIS都包含一个名为的功能 **on-the-fly** 投影。这意味着，你可以 **define** 启动GIS时的某个投影和随后加载的所有层，无论它们具有什么坐标系，都将自动显示在您定义的投影中。此功能允许您在GIS的地图窗口内叠加图层，即使它们可能位于中 **different** 参考系。在QGIS中，默认情况下应用此功能。





#  常见的两种地图投影：Gauss-Kruger vs UTM

> https://zhuanlan.zhihu.com/p/659373326



地球是圆的，要把它放到一个平面上就需要投影。常用的投影方法有两种，高斯-克吕格投影（Gauss-Kruger）与通用横轴墨卡托投影（Universal Transverse Mercator，UTM）。本文将介绍二者的定义、分带计算及异同。

## **1、高斯-克吕格投影**

高斯-克吕格(Gauss-Kruger)投影，是一种“等角横切圆柱投影”。德国数学家、物理学家、天文学家高斯拟定，后经德国大地测量学家克吕格于1912年对投影公式加以补充。设想用一个圆柱横切于球面上投影带的中央经线，按照投影带中央经线投影为直线且长度不变和赤道投影为直线的条件，将中央经线两侧一定经差范围内的球面正形投影于圆柱面。然后将圆柱面沿过南北极的母线剪开展平，即获高斯一克吕格投影平面。高斯一克吕格投影后，除中央经线和赤道为直线外，其他经线均为对称于中央经线的曲线。高斯-克吕格投影没有角度变形，在长度和面积上变形也很小，中央经线无变形，自中央经线向投影带边缘，变形逐渐增加，变形最大处在投影带内赤道的两端。按一定经差将地球椭球面划分成若干投影带，这是高斯投影中限制长度变形的最有效方法。分带时既要控制长度变形使其不大于测图误差，又要使带数不致过多以减少换带计算工作，据此原则将地球椭球面沿子午线划分成经差相等的瓜瓣形地带，以便分带投影。

　　通常按经差6度或3度分为六度带或三度带。六度带自0度子午线起每隔经差6度自西向东分带，带号依次编为第1、2…60带。三度带是在六度带的基础上分成的，它的中央子午线与六度带的中央子午线和分带子午线重合，即自1.5度子午线起每隔经差3度自西向东分带，带号依次编为三度带第 1、2…120带。我国的经度范围西起73°东至135°，可分成六度带十一个，各带中央经线依次为75°、81°、87°、……、117°、123°、129°、135°，或三度带二十二个。我国大于等于50万的大中比例尺地形图多采用六度带高斯-克吕格投影，三度带高斯-克吕格投影多用于大比例尺测图，如城建坐标多采用三度带的高斯-克吕格投影。

## **2、UTM投影**

　　UTM投影全称为“通用横轴墨卡托投影”(Universal Transverse Mercator)，是一种“等角横轴割圆柱投影”，椭圆柱割地球于南纬80度、北纬84度两条等高圈，投影后两条相割的经线上没有变形，而中央经线上长度比0.9996。**美国于1948年完成这种通用投影系统的计算**。与高斯-克吕格投影相似，**该投影角度没有变形，中央经线为直线，且为投影的对称轴，中央经线的比例因子取0.9996是为了保证离中央经线左右约330km处有两条不失真的标准经线**。UTM投影分带方法与高斯-克吕格投影相似，是自西经180°起每隔经差6度自西向东分带，将地球划分为60个投影带。

> 自西经180°起每隔经差6度自西向东分带，将地球划分为**60个投影带。**
>
> **在美国本土采用Clarke 1866椭球体以外，UTM在世界其他地方都采用WGS84。**

UTM (Universal Transverse Mercator)坐标系是由美国军方在1947提出的。虽然我们仍然将其看作与“高斯－克吕格”相似的坐标系统，但实际上UTM采用了[网格](https://link.zhihu.com/?target=https%3A//so.csdn.net/so/search%3Fq%3D%E7%BD%91%E6%A0%BC%26spm%3D1001.2101.3001.7020)的分带（或分块）。除在美国本土采用Clarke 1866椭球体以外，UTM在世界其他地方都采用WGS84。 UTM是由美国制定，因此起始分带并不在本初子午线，而是在180度，因而所有美国本土都处于0－30带内。UTM投影采用6度分带，从东经180度（或西经180度）开始，自西向东算起，因此1带的中央经线为-177（-180 -(-6)），而0度经线为30带和31带的分界，这两带的分界分别是-3和3度。纬度采用8度分带，从80S到84N共20个纬度带（X带多4度），分别用C到X的字母来表示。为了避免和数字混淆，I和O没有采用。UTM的“false easting”值为500km，而南半球UTM带的“false northing”为10000km.。



![img](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/v2-cfd460d6bd4b65eec26baa4c610a2875_720w.webp)

UTM投影



![动图](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/e8d3e27e73a811b364b0f8141fee78a0_b.webp)



墨卡托投影原理图

“WGS 1984”坐标系的墨卡托投影分度带（UTM ZONE）选择方法如下：

（1） 北半球地区，选择最后字母为“N”的带；
（2） 可根据公式计算，带数=（经度整数位/6）的整数部分+31 如：江西省南昌新建县某调查单元经度范围115°35′20″—115°36′00″， 带数=115/6+31=50，选50N，即**WGS 1984 UTM ZONE 50N**。

中国UTM投影带号

中国国境所跨UTM带号为43-53 我国的疆域范围：
最西端 北纬39度15分、东经73度33分 最北端 北纬53度33.5分 东经124度27分 最南点，处北纬3°51′，东经112°16′ 最东端 北纬47度27.5分 东经134度46.5分

UTM投影带号计算

如WGS_1984_UTM_Zone_49N，这个带号49的计算方法：
49：从180度经度向东,每6度为一投影带,第49个投影带
49=（114+180）/6，这个114为49投影带的最大经线

## **3、高斯-克吕格投影与UTM投影异同**

　　高斯-克吕格投影与UTM投影都是横轴墨卡托投影的变种，很多软件往往不支持高斯-克吕格投影，但支持UTM投影，因此常有把UTM投影当作高斯-克吕格投影的现象。

　　从投影几何方式看，高斯-克吕格投影是“等角横切圆柱投影”，投影后中央经线保持长度不变，即比例系数为1；UTM投影是“等角横轴割圆柱投影”，圆柱割地球于南纬80度、北纬84度两条等高圈，投影后两条割线上没有变形，中央经线上长度比0.9996。从计算结果看，两者主要差别在比例因子上，高斯-克吕格投影中央经线上的比例系数为1，UTM投影为0.9996，高斯-克吕格投影与UTM投影可近似采用 X[UTM]=0.9996 * X[高斯]，Y[UTM]=0.9996 * Y[高斯]，进行坐标转换（注意：如坐标纵轴西移了500000米，转换时必须将Y值减去500000乘上比例因子后再加500000）。

　　从分带方式看，两者的分带起点不同，高斯-克吕格投影自0度子午线起每隔经差6度自西向东分带，第1带的中央经度为3°；UTM投影自西经180°起每隔经差6度自西向东分带，第1带的中央经度为-177°，因此高斯-克吕格投影的第1带是UTM的第31带。此外，两投影的东伪偏移都是500公里，高斯-克吕格投影北伪偏移为零，UTM北半球投影北伪偏移为零，南半球则为10000公里。

## **4、高斯-克吕格投影与UTM投影坐标系**

　　高斯-克吕格投影与UTM投影是按分带方法各自进行投影，故各带坐标成独立系统。以中央经线（L0）投影为纵轴X，赤道投影为横轴Y，两轴交点即为各带的坐标原点。为了避免横坐标出现负值，高斯-克吕格投影与UTM北半球投影中规定将坐标纵轴西移500公里当作起始轴，而UTM南半球投影除了将纵轴西移500公里外，横轴南移10000公里。由于高斯-克吕格投影与UTM投影每一个投影带的坐标都是对本带坐标原点的相对值，所以各带的坐标完全相同，**为了区别某一坐标系统属于哪一带，通常在横轴坐标前加上带号。**

## **5、高斯-克吕格投影分带方法**

### a．我国采用6度分带和3度分带

**1∶2.5万及1∶5万的地形图采用6度分带投影，即经差为6度**，从零度子午线开始，自西向东每个经差6度为一投影带，全球共分60个带，用1，2，3，4，5，……表示。即**东经0～6度为第一带**，其中央经线的经度为东经3度，东经6～12度为第二带，其中央经线的经度为9度。

> **从零度子午线开始**

![img](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/v2-e77eaadb4ac610b3c9b4653a6797bcd6_720w.webp)

**1∶1万的地形图采用3度分带，从东经1.5度的经线开始，每隔3度为一带**，用1，2，3，……表示，全球共划分120个投影带，即东经1.5～4.5度为第1带，其中央经线的经度为东经3度，东经4.5～7.5度为第2带，其中央经线的经度为东经6度。

> ![img](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/4q19_agmap_1.jpg)

### b．当地中央经线经度的计算

六度带中央经线经度的计算：当地中央经线经度＝6°×当地带号－3°(适用于1∶2.5万和1:5万地形图)。

三度带中央经线经度的计算：中央经线经度＝3°×当地带号(适用于1∶1万地形图)。

![img](./%E4%B8%AD%E5%A4%AE%E7%BB%8F%E7%BA%BF%EF%BC%88Central%20Meridian%EF%BC%89%E8%A7%A3%E9%87%8A.assets/v2-fbab85f69d0644a5d44e7949e062b59d_720w.webp)

## 小结

- 高斯克吕格投影是一种“等角横切圆柱投影”，起点在零度本初子午线；UTM又称横向墨卡托投影，是一种“等角横轴割圆柱投影”，起点在180度经线。二者均是自西向东计算带号。
- 高斯克吕格投影有6度带（用于 1∶2.5万及1∶5万的地形图）和3度带（用于 1∶1万及以下的大比例尺地形图）之分。而UTM只有6度分带。因此高斯克吕格投影有60个带（6度带）或120个带（3度带），而UTM只有60个带。
- 我国常用高斯克吕格投影，欧美多使用UTM投影。
- 知道投影方式、带号和公里坐标，两种投影方式均可通过简单计算转换为经纬度。在线转换网页见参考资料。

## 参考资料

> [UTM投影分带标准_utm 3度带的对应关系-CSDN博客](https://link.zhihu.com/?target=https%3A//blog.csdn.net/ivan_ljf/article/details/52637293)
>
> [高斯-克吕格投影和UTM投影 - 南宁市锐博影像科技有限公司](https://link.zhihu.com/?target=http%3A//www.imagerb.com/nd.jsp%3Fid%3D32)
>
> [Gauss-Kruger Projection](https://link.zhihu.com/?target=http%3A//ikcest-drr.osgeo.cn/tutorial/k1044)
>
> [Convert Gauss-Kruger (GK) coordinates to Latitude/Longitude](https://link.zhihu.com/?target=https%3A//community.qlik.com/t5/QlikView-Documents/Convert-Gauss-Kruger-GK-coordinates-to-Latitude-Longitude/ta-p/1487143)
>
> [Lat/Lon and UTM Conversion](https://link.zhihu.com/?target=http%3A//rcn.montana.edu/resources/Converter.aspx)
>
> [WGS84 Lat/Long or Gauß-Krüger to Grid Reference](https://link.zhihu.com/?target=http%3A//geo-en.hlipp.de/latlong.php)
>
> [Online converter to all coordinate systems](https://link.zhihu.com/?target=https%3A//coordinates-converter.com/en/decimal/51.000000%2C10.000000%3Fkarte%3DOpenStreetMap%26zoom%3D8)
>
> 发布于 2023-10-03 05:43・IP 属地瑞士
>







