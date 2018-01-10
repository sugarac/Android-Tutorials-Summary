[/回调函数（callback）是什么？ - no.body的回答 - 知乎 https://www.zhihu.com/question/19801131/answer/27459821](/回调函数（callback）是什么？ - no.body的回答 - 知乎 https://www.zhihu.com/question/19801131/answer/27459821)

回调有三个部分组成：回调函数、中间函数和起始函数

举个住旅馆叫醒服务的例子：

1.旅馆提供叫醒服务是起始函数

2.有三种叫醒旅客的方式：打电话叫、服务员敲门叫，在你头上浇盆水，这三种叫醒方式属于三种回调函数

3.旅客通知旅馆使用何种叫醒方式的动作，属于中间函数

一、创建三种回调函数：

1.morning\_call\(me\)

2.knocking\_door\(me\)

3.watering\_head\(me\)

二、创建中间函数：

def ask\_for\_wakeup\(people, call\_function\)

return call\_function\(people\)

三、用起始函数（主函数）来做这件事情

def main\(\):

return ask\_for\_wakeup\('Antony', watering\_head\)

酱紫，最后一部调用回调函数，又返回回调函数，最终得到结果

