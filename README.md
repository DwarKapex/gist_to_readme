<script 
type="text/javascript">
var $table = $('#table');
$.getJSON('https://gist.githubusercontent.com/TheMightyLlama/9f4f1b4c2c078a6080c9212aba6beb59/raw/092fc02afcbd11ea26e7a08541b8dfae4748218a/News%2520Summary%2520Sample', function(mydata) {
    $('#table').bootstrapTable({
        data: mydata
    });
});
</script>
<div class="container">
  <table id="table" data-height="460">
    <thead>
      <tr>
        <th data-field="title">Title</th>
        <th data-field="date">Date</th>
        <th data-field="category">Category</th>
      </tr>
    </thead>
  </table>
</div>

