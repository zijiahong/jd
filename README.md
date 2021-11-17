
> 
>   清单(仅供参考）：  
##############长期活动##############
 京东汽车(签到满500赛点可兑换500京豆)0 0 * * * node /scripts/jd_car.js    /scripts/logs/jd_car       
 京东家庭号(暂不知最佳cron) */20 * * * * node /scripts/jd_family.js    /scripts/logs/jd_family       
 京东抽奖机11 1 * * * node /scripts/jd_lotteryMachine.js >> /scripts/logs/jd_lotteryMachine      
 点点券20 0,20 * * * node /scripts/jd_necklace.js >> /scripts/logs/jd_necklace      
 微信小程序京东赚赚10 11 * * * node /scripts/jd_jdzz.js    /scripts/logs/jd_jdzz       
 crazyJoy自动每日任务10 7 * * * node /scripts/jd_crazy_joy.js    /scripts/logs/jd_crazy_joy       
 京东秒秒币10 7 * * * node /scripts/jd_ms.js    /scripts/logs/jd_ms       

