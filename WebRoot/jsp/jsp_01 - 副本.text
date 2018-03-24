<%@ page import="java.text.SimpleDateFormat"%>
<%@ page language="java" import="java.util.*" contentType="text/html; charset=UTF-8"
pageEncoding="UTF-8"%>
<%@ include file="base.jsp" %>

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
<html>
  <head>
    <title></title>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  </head>
  <body>
    <!-- 什么是jsp？简单来说就是在html代码里面嵌入java代码这就是jsp，jsp文件是以.jsp结尾的 -->
    <!-- jsp里面主要有如下内容 -->
    <h1>1.注释</h1>
    
    <!-- 这是html注释 ，特点是在客户端可见-->
    <%--这是jsp的注释 ，特点是在客户端不可见--%>
    
    <h1>2.jsp指令</h1>
    
    <h1>3.jsp小脚本：简单来说就是在jsp页面嵌入java代码</h1>
    <%
    	//这里面的java代码该怎么写怎么写
    	Date d = new Date();
    	System.out.println(d);
    	SimpleDateFormat sdf = new SimpleDateFormat("yyyy-MM-dd HH:mm:ss");
    	String s = sdf.format(d);
    	System.out.println(s);
     %>
     
     <h1>4.jsp声明：在jsp页面定义变量或者方法</h1>
     
     <%!
     	String st = "HELLO";
     	public int add(int a,int b){
     		 return a + b;
     	}
      %>
      
      <h1>5.jsp表达式</h1>
      
      <%=st %><br/>
      <%=add(10,30) %><br/>
      <%=d %><br/>
      <%=s %><br/>
      
      <%
      	System.out.println(s);
      	System.out.println(st);
       %>
       
       <h1>6.静态内容（html内容）</h1>
  </body>
</html>
