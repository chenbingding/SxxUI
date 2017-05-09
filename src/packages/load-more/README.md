
# 组件安装方法：
 *   #1 引入Vue && DatetimePicker组件
 *     import Vue from 'Vue' 
 *     import LoadMore from 'xxx/load-more'
 *   #2 安装组件
 *     Vue.component(LoadMore.name, LoadMore);
 * 
# 用法：
 *   <sxx-load-more></sxx-load-more>
 * 
# options说明：
   {
  	   type: '', //组件的类型，可选值：'datetime'、'date'、'time'，默认值：'datetime'，[type: String]

       defaultDatetime: '', // 组件默认选中日期/时间，默认值为当前日期/时间，[type: String]，

 						// 格式为：yyyy-MM-dd HH:mm:ss或yyyy-MM-dd或HH:mm:ss

       startDate: '', // 日期的最小可选值，默认为十年前的1月1日，[type: String]，

 					  // 格式为：yyyy-MM-dd

       endDate: '', // 日期的最大可选值，默认为十年后的 12 月 31 日，[type: String]，

 					// 格式为：yyyy-MM-dd

 	   startHour: '', // 小时的最小可选值，默认为：0，[type: Number]

 	   endHour: '', // 小时的最大可选值，默认为：23，[type: Number]

  	   confirm: '', // 回调函数，在点击确认之后执行，[type: Function]，
  	   				// 函数接受一个参数，参数是返回的选中的日期/时间，返回日期/时间格式为：yyyy-MM-dd HH:mm:ss或yyyy-MM-dd或HH:mm:ss

 	   cancel: '' // 回调函数，在点击取消之后执行，[type: Function]
   }