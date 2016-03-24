# jtree-list #

a jquery plugin of tree list

## How To Use ##

```
<link rel="stylesheet" type="text/css" href="css/tree-list.css">
```

```
<script src="http://lib.sinaapp.com/js/jquery/1.9.1/jquery-1.9.1.min.js"></script>
```

```
<script type="text/javascript" src='treelist.js'></script>
```

html:

```
<div class="tree-list">  //class name must be tree-list
  <ul>
    <li>财务管理
      <ul>
        <li>应收款管理
          <ul>
            <li>应收账款</li>
            <li>欠条</li>
            <li>利息</li>
          </ul>
        </li>
        <li>应付款管理</li>
        <li>预算管理</li>
      </ul>
    </li>
    <li>供应链
      <ul>
        <li>销售管理</li>
        <li>采购管理</li>
        <li>库存管理</li>
      </ul>
    </li>
    <li>管理会计
      <ul>
        <li>成本会计</li>
      </ul>
    </li>
  </ul>
</div>
```

```
<script type="text/javascript">
  $(function(){
    $.treelist();
  })
</script>
```
