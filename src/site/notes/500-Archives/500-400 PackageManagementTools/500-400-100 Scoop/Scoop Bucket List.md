---
{"dg-publish":true,"permalink":"/500-archives/500-400-package-management-tools/500-400-100-scoop/scoop-bucket-list/"}
---


Time: 2022-09-14 17:18:01
UTCK: 20220914171801
Link: [[500-Archives/500-400 PackageManagementTools/500-400-100 Scoop/Scoop Bucket List\|]]
Tags: #Software/PackageManagementTools/Scoop

------

Record:
# [[500-Archives/500-400 PackageManagementTools/500-400-100 Scoop/Scoop\|Scoop]] 的常用 `Bucket` 列表：
1. 常用命令：
	1. `scoop bucket list`
	2. `scoop bucket add <bucketname> <bucketurl>`
	3. `scoop bucket remove`
	4. `scoop bucket known`
	5. `scoop help bucket`
2. 官方库：
	1. [`main`](https://github.com/ScoopInstaller/Main)：默认主库 
	2. [`extras`](https://github.com/ScoopInstaller/Extras): 扩展库存 `scoop bucket add extras`
	3. [`versions`](https://github.com/ScoopInstaller/Versions) : 版本库存 `scoop bucket add versions`
	4. [`nonportable`](https://github.com/ScoopInstaller/Nonportable): 非便携版软件库存 `scoop bucket add nonportable`
	5. [`java`](https://github.com/ScoopInstaller/Java) : 官方[[Java\|Java]]库 `scoop bucket add java`
3. 第三方库
	1. [`dorado`](https://github.com/chawyehsu/dorado): 著名的第三方库，包含众多国内应用 `scoop bucket add dorado https://github.com/chawyehsu/dorado`
	2. [`MorFans-apt`](https://github.com/Paxxs/Cluttered-bucket.git):第三方库 `scoop bucket add MorFans-apt https://github.com/Paxxs/Cluttered-bucket.git`
	3. [`spoon`](https://github.com/FDUZS/spoon.git)：第三方库 `scoop bucket add spoon https://github.com/FDUZS/spoon.git`
4. ![](https://evanlee-img-service.oss-accelerate.aliyuncs.com/20220914173304.png)



------

Note:
[[500-Archives/500-400 PackageManagementTools/500-400-100 Scoop/Scoop Bucket List\|]] -

------

Refer:
1. [scoop，一条命令安装windows软件 - 掘金](https://juejin.cn/post/7125209151151538184)