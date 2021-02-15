# Cloudflare-ERROR-524

All **styles and pictures** in one file.

# Add php

Add functionality

	<?php
	//Server name
	$uri = 'http://'.$_SERVER['SERVER_NAME']; 
	//Server IP
	$ip = $_SERVER['SERVER_ADDR'];
	//Site name
	$sitename = $_SERVER['SERVER_NAME'];
	//Ray ID
	$permitted_chars = '0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ';
	$rayid = substr(str_shuffle($permitted_chars), 0, 16);
	//Date and time
	$time = date("Y-m-d g:i:s T"); 
	?>