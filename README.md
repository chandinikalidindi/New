<!DOCTYPE html>
<html>
<head>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="notify.js"></script>
</head>
<body>
   <button type="button" id="button1" onclick="AlertUser()">AutoDismissible button</button>
   <br/>
   <script language="javascript">
      function AlertUser()
	  {
	     $.notify('Poda paavi. billa bittiri... heheheheheh.... neekidi chaaldu inka ekkuva ivvu');
	  }
   </script>
</body>
</html>
