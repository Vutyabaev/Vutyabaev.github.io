var resolve = require('onetwo')

resolve('noffle', 'test', function (err, value) {
  if (err) return console.log(err)

  console.log('value:', value)
})
