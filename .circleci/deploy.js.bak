var FtpDeploy = require('ftp-deploy');
var ftpDeploy = new FtpDeploy();
 
var config = {
    username: process.env.ftp_user_id,
    password: process.env.ftp_pass,
    host: process.env.ftp_user_id,
    port: 21,
    localRoot: __dirname + "/../dist/",
    remoteRoot: "/",
    include: ['*']
}
    
ftpDeploy.deploy(config, function(err) {
    if (err) console.log(err)
    else console.log('finished');
});