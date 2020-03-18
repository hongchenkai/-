<div id="container"></div>
<link rel="stylesheet" href="https://imsun.github.io/gitment/style/default.css">
<script src="https://imsun.github.io/gitment/dist/gitment.browser.js"></script>
<script>
var gitment = new Gitment({
  id: location.href', // 可选。默认为 location.href
  owner: '2398954487',
  repo: 'pinlunchucun',
  oauth: {
    client_id: '68ccf47cc39192340bd5,
    client_secret: '10218a0dc68ed606f3e8801189c33212931be229',
  },
})
gitment.render('container')
</script>
