##  Good Sessions

* [Day 2 Keynote](https://www.youtube.com/watch?v=ZPbM2qGfH3s)
* [Lightning  Fast Deploys with Docker Containers and AWS](https://www.youtube.com/watch?v=q4MVVL6rmd4)
* [Amazon EC2 Conrtainer Service](https://www.youtube.com/watch?v=2vJLS8qfhI0)
* [Monitoring and Runnig Docker Containers at Scale](https://www.youtube.com/watch?v=RRm3HUCXvyU)
* [How Netflix' Open Source Tools Help Accelerate & Scale Service](https://www.youtube.com/watch?v=p7ysHhs5hl0)
* [Advanced Usage of the AWS CLI](https://www.youtube.com/watch?v=vP56l7qThNs)
* [Optimizing Your Web Server on AWS](https://www.youtube.com/watch?v=ZfY0kwYiBRY)

note:
    Day 2 Keynote とにかくECSのdemoがかっこよかったので、ぜひ見てください
    Lightning Fast Deploys ry Dockerの中の人のsessionで、docker commandをシェルスクリプトでラップしてるんですが、
        この人の遊びみたいなsessionで、とてもfunnyなsessionでした
    Amazon EC2 Container Service 今のところ、ECSが今後どういうサポートをしていくのか(ELB Integrationとか)をしゃべってるところは、
        調べたところ、これだけでした。コンテナ間の通信(どのポートをserver側のlistenポートとしてあけるかとか)の定義とかもしてて、
        オーケストレーション、って感じのsessionでした
    Monitoring and Runnig ry Datadogの広告みたいなとこもあったんですが、Immutableなserverを運用してると、事前にホストの定義とかが
        必要な監視システムが崩壊するので、DatadogのEC2ホストとEC2上のContainerを勝手に監視してくれるってのは魅力的でした
    How Netflix' Open Source Tools Help Accelerate ry
        Netflixが自分たちで作って自分たちで使ってるOSSを紹介してるsessionで、正直全部が全部使えるかって言われるとそんなことはないんですが
        Security MonkeyっていうSecurity Holeを探してくれたり、AWSのLimitationを通知してくれるシステムがよさげでした
    Optimizing Your Web Server on AWS
        Web Serverのチューニングについてのsessionで、今一度KeepAliveについて考えたり、NginxやApacheのconfigに合わせた
        kernel parameterを紹介してくれてました
        あと、このセッションでログは嘘をつかないみたいな話があるんですが、なんとなくログを眺めるんじゃなくて、
        どのURIが重いかとか、HTTP Method単位で見ろとか、ちゃんとログの中身を理解した監視をしましょうって話でした
