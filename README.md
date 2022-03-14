# Vue-axios

##音乐播放器
<hr>

###1.歌曲搜索接口
<ul>
  <li>请求地址:https://autumnfish.cn/search</li>
  <li>请求方法:get</li>
  <li>请求参数:keywords(查询关键字)</li>
  <li>响应内容:歌曲搜索结果</li>
</ul>

###2.歌曲url获取接口
<ul>
  <li>请求地址:https://autumnfish.cn/song/url</li>
  <li>请求方法:get</li>
  <li>请求参数:id(歌曲id)</li>
  <li>响应内容:歌曲url地址</li>
</ul>

###3.歌曲详情获取
<ul>
  <li>请求地址:https://autumnfish.cn/song/detail</li>
  <li>请求方法:get</li>
  <li>请求参数:ids(歌曲id)</li>
  <li>响应内容:歌曲详情(包括封面信息)</li>
</ul>

 ###4.热门评论获取
 <ul>
  <li>请求地址:https://autumnfish.cn/comment/hot?type=0</li>
  <li>请求方法:get</li>
  <li>请求参数:id(歌曲id,地址中的type固定为0)</li>
  <li>响应内容:歌曲的热门评论</li>
 </ul>
 
 ###5.mv地址获取
 <ul>
  <li>请求地址:https://autumnfish.cn/mv/url</li>
  <li>请求方法:get</li>
  <li>请求参数:id(mvid,为0表示没有mv)</li>
  <li>响应内容:mv的地址</li>
</ul>
