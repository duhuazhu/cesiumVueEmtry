<!--
 * @version: 1.0.0
 * @Author: duhuazhu<335921101@qq.com>
 * @Date:2022-05-12 15:08:22
-->
<template>


<!--顶部   分成五部分  logo标题  查询  tab切换  常用菜单  登录设置类 -->



<!--左侧 存放功能-->
<!--  cesium主视图-->
  <map3d/>
</template>

<script>
import map3d from "@/components/map3d";
export default {
  name: 'CesiumContainer',
  components:{map3d},
}
</script>
