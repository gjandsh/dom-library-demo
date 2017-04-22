# dom-library-demo
#需求
let items = $('li')

items.on('click', function(){
  console.log('click')
})

items.addClass('hi').removeClass('error')

items.text('你好')
textList = items.text()

items.get(0)

$item.siblings().addClass('active')

$item.siblings().removeClass('active').end().addClass('active')
