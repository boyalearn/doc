   
   项目POM中配置这个能够知道这个发布到那个服务器
   <distributionManagement>
        <snapshotRepository>
            <id>fast-snapshots</id>
            <name>fast-snapshots</name>
            <url>http://nexus.chinacloud.com.cn/repository/fast-snapshots</url>
        </snapshotRepository>
    </distributionManagement>
