###Rcowteach

####Introduction
one command a day , stupid leave you away  
![cowteach](http://ringtail.u.qiniudn.com/ba0172ce9e25a039f2877ad855ae9da4.png)

####Install in linux or mac
#####linux
<pre>
	<code>
		//ubuntu or mint
		sudo apt-get install cowsay
		
		//fedora
		yum install cowsay
		
		
		//open the bash_profile and append the commands blow
		cowsay -f $(ls /usr/local/Cellar/cowsay/3.03/share/cows | shuf -n 1 | cut -d. -f1) $(whatis $(ls /bin) 2>/dev/null | 	shuf -n 1)
		
		//replace with you cows path, use cowsay '-l' to find the cows path 
	</code>
</pre>

####mac
<pre>
	<code>
		//install gshuf
		brew install coreutils
		
		//install cowsay
		brew install cowsay
		
		//write the commands blow into the ~/.bash_profile
		cowsay -f $(ls /usr/local/Cellar/cowsay/3.03/share/cows | gshuf -n 1 | cut -d. -f1) $(whatis $(ls /bin) 2>/dev/null | gshuf -n 1)
	</code>
</pre>

####enjoy your cowteach
![cowteach](http://ringtail.u.qiniudn.com/87d29bbdea1c8380404a4a7a7119bbc6.png)
![cowteach](http://ringtail.u.qiniudn.com/fc7ae4aee34cfdae80deab725dc09091.png)

