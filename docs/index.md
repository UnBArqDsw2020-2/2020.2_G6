<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>NomeX</title>
  <link rel="icon" href="assets/logo/">
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <meta name="description" content="Description">
  <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/docsify-themeable@0/dist/css/theme-simple.css">
  <link rel="stylesheet" href="assets/css/sidebar.css">
  <link href="./assets/css/index.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
  <style>
    :root{
      --base-font-family: 'Montserrat', sans-serif;
      --base-font-size: 16px;
      --theme-color   : #4b8ab9;
    }
  </style>
</head>
<body>
  <div id="app"></div>
  <script>
    window.$docsify = {
      name: 'NomeX',
      coverpage: true,
      requestHeaders: {
        'cache-control': 'no-cache'
      },
      subMaxLevel: 02,
      logo:"./assets/logo/",
      repo: 'https://github.com/UnBArqDsw2020-2/2020.2_G6',
      loadSidebar: true,
    }
  </script>
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
  <script src="//unpkg.com/docsify-sidebar-collapse/dist/docsify-sidebar-collapse.min.js"></script>
</body>
</html>