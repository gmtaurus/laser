# laser
一、激光进度条
异步请求发出前，Math.random()*100初始化进度条的width，请求返回后，
if（success）{
  进度条width：100%;
}else{
  进度条width：0;
}
二、雪碧图&&animation的应用
雪碧图 background-position 定位&& animation结合，利用animation 中steps(),完成一组动画
