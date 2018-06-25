# area
2018-6-25最新全国行政三级联动 js插件
## 插件描述：jQuery省市三级联动(最新全国行政三级联动)

## 使用方法

### 1：加载jQuery库.
<script src="http://www.jq22.com/jquery/jquery-1.10.2.js"></script>

### 2：加载js文件
<script src="area.js"></script>

### 3 执行
addressInit('province', 'city', 'district', '安徽', '合肥市', '蜀山区');
//province 省select下拉框的class ；city市class；district区县class
//安徽、合肥市、蜀山区  默认；可为空

### 4 举个列子
 ```  
 <div class="row">
     <select class=" province" name="province"></select>
     <select class=" city" name="city"></select>
     <select class=" district" name="district" ></select>
 </div>
 <script type="text/javascript">
    //province 省select下拉框的class ；city市class；district区县class
    //安徽、合肥市、蜀山区  默认；可为空
	addressInit('province', 'city', 'district', '广东', '深圳', '南山区');
</script>
 ```
