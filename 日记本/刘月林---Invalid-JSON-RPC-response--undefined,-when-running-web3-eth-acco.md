I'm very new Ethereum and trying to follow this tutorial:
https://www.zastrin.com/courses/simple-voting-vid/lessons/3-4

But when I run:
deployedContract = VotingContract.new(['Rama','Nick','Jose'],{data: byteCode, from: web3.eth.accounts[0], gas: 4700000})

I get an error:
![屏幕快照 2018-07-18 下午4.32.50.png](https://upload-images.jianshu.io/upload_images/13089440-084802c44bbb9247.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

Solution:
Install web3 and testrpc packages: npm install ethereumjs-testrpc web3@0.20.1 In the same terminal window, run testrpc: 
node_modules/.bin/testrpc Open a NEW terminal window (with the first one still open and running), and run node :

deployedContract = VotingContract.new(['Rama','Nick','Jose'],{data: byteCode, from: web3.eth.accounts[0], gas: 4700000})
![环境配置2.gif](https://upload-images.jianshu.io/upload_images/13089440-5fed2bfb7d3cd708.gif?imageMogr2/auto-orient/strip)

Finally, succeeded!

刘月林
写于湖北沙洋
2018/07/18
