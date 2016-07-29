# datePicker
datePicker 整理的日历插件

开发过程中 头疼了很多日历插件 很多都不近人意 要么不能初始化 要么有些小的bug

这个插件是至今觉得很不错的一个整理过的日历插件 简洁方便

  $.fn.datepicker.languages['zh-CN'] = {
        format: 'yyyy-mm-dd',
        days: ['星期日', '星期一', '星期二', '星期三', '星期四', '星期五', '星期六'],
        daysShort: ['周日', '周一', '周二', '周三', '周四', '周五', '周六'],
        daysMin: ['日', '一', '二', '三', '四', '五', '六'],
        months: ['一月', '二月', '三月', '四月', '五月', '六月', '七月', '八月', '九月', '十月', '十一月', '十二月'],
        monthsShort: ['1月', '2月', '3月', '4月', '5月', '6月', '7月', '8月', '9月', '10月', '11月', '12月'],
        weekStart: 0,
        yearFirst: true,
        yearSuffix: '年',
        autohide: true,
        daystyle: 'short',
        zIndex: 1040
    };


这个是中文格式化代码
