# ZhihuDaily RSS Generator 知乎日报RSS生成器

利用知乎日报API实现

## Crontab 定时更新命令

    wget {$url}/fetch.php -O - > /dev/null 2>&1

## Windows下可使用计划任务执行

    wget {$url}/fetch.php -O    

## rss订阅器使用url

* 订阅：<domain>/index.php
* 即时抓取：<domain>/zhihu.php (如果是使用这种方式，则不需要配置上面的定时抓取)

## Demo 可直接订阅(已无效)

> [http://zhihudaily.dev.malash.net/](http://zhihudaily.dev.malash.net/ "知乎日报RSS")

## Powered by 

* Malash([http://malash.me/](http://malash.me/ "Malash"))
* k1988([http://k1988.github.com/](http://k1988.github.com/ "k1988"))