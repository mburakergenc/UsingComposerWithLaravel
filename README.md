UsingComposerWithLaravel
========================

A simple example that explains the usage of composer with Laravel PHP Framework

What is Composer 
========================

Basically composer is a dependency manager for PHP. It allows us to get dependencies just by updating the json file. These dependencies may be about authentication, caching or file generators. Any or all of these tools can be pulled from Composer. If you really want to learn Laravel you must know about composer, because Laravel uses Composer so much. 

How to Install Composer
========================
Go to https://getcomposer.org/doc/00-intro.md and select the version that you want do download. In my case I'm using mac, so continue with the mac version.

Open up your terminal and write the following command.

<pre class=" language-bash"><code class=" language-bash">curl -sS https://getcomposer.org/installer | php
</code></pre>

That's it you just downloaded the composer, however if you would like to access to composer anywhere on you machine you should move the composer.phar file to your bin directory. To do that write the following command;

<pre class=" language-bash"><code class=" language-bash">mv composer.phar /usr/local/bin/composer</code></pre>

and that's it!. You can now call the composer command anywhere on your machine. 




