# GD-V2ray-ansible
## License

This project is licensed under the MIT License.
See the [LICENSE](./LICENSE) file for details.

使用v2ray配合ansible来实现批量搭建科学上网代理服务器，来实现科学上网，自动化批量部署代理服务器节点，使用文档说明十分清楚，使用前需要购买境外云服务器，并且在主控节点配置ansiible，文档中的代理节点只是作为演示使用，目前文档中的代理服务器已经关闭，请大家自行购买代理节点或寻找可用的可操作的代理节点进行搭建

如果需要使用导航器执行剧本，那么就是从百度网盘中下载这个ansible-rhel9.iso
通过网盘分享的文件：ansible-rhel9.iso
链接: https://pan.baidu.com/s/1aOcfeuU6pegFaxNyRbmHNA?pwd=8888 提取码: 8888 
--来自百度网盘超级会员v1的分享

v2ray.tar.gz这个压缩文件中包含roles角色和执行角色的playbook剧本，下载之后解压，将这个playbook剧本与roles放到/etc/ansible，通过playbook剧本运行这个角色就好，最好ansible.cfg与我文档中的配置相同，不然可能会出现报错信息
