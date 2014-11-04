19:00 -!- ircretary [~ircretary@165.225.132.207] has quit [Remote host closed
          the connection]
19:00 -!- ircretary [~ircretary@165.225.132.207] has joined #stackvm
19:01 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has quit [Quit:
          dguttman]
19:05 -!- anvaka [~anvaka@216.243.14.85] has quit [Remote host closed the
          connection]
19:07 -!- tilgovi [~randall@couchdb/committer/tilgovi] has quit [Remote host
          closed the connection]
19:09 -!- stagas [~stagas@ppp-2-84-86-244.home.otenet.gr] has quit [Ping
          timeout: 272 seconds]
19:11 -!- domanic [~domanic@d51528182.access.telenet.be] has quit [Ping
          timeout: 244 seconds]
19:11 -!- ins0mnia [~smuxi@81-234-249-196-no52.tbcn.telia.com] has quit [Ping
          timeout: 255 seconds]
19:14 -!- ins0mnia [~smuxi@81-234-249-196-no52.tbcn.telia.com] has joined
          #stackvm
19:19 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has joined
          #stackvm
19:32 -!- Ursium [~Ursium@cpc2-mort5-2-0-cust245.croy.cable.virginm.net] has
          quit [Quit: Off I go]
19:33 -!- Ursium [~Ursium@cpc2-mort5-2-0-cust245.croy.cable.virginm.net] has
          joined #stackvm
19:44 -!- anvaka [~anvaka@2601:8:ac80:3f9:8cc6:b1ff:7e7c:c30e] has joined
          #stackvm
19:50 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          joined #stackvm
20:27 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          quit [Quit: ryan_stevens]
21:05 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has joined #stackvm
21:20 -!- ednapiranha [~ednapiran@c-71-193-203-43.hsd1.or.comcast.net] has
          joined #stackvm
21:38 -!- toddself [~toddself@pool-173-68-17-221.pghkny.fios.verizon.net] has
          joined #stackvm
21:40 -!- ednapiranha [~ednapiran@c-71-193-203-43.hsd1.or.comcast.net] has quit
          [Remote host closed the connection]
21:53 -!- anvaka [~anvaka@2601:8:ac80:3f9:8cc6:b1ff:7e7c:c30e] has quit [Remote
          host closed the connection]
21:55 -!- contrahax [~contrahax@ip24-251-13-101.ph.ph.cox.net] has joined
          #stackvm
21:56 -!- contrahax is now known as _contrahax
22:00 -!- toddself [~toddself@pool-173-68-17-221.pghkny.fios.verizon.net] has
          quit []
22:25 -!- Mso150 [~ctlM@80.83.239.84] has joined #stackvm
22:30 -!- anvaka [~anvaka@c-76-121-53-98.hsd1.wa.comcast.net] has joined
          #stackvm
22:36 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          joined #stackvm
22:49 -!- anvaka [~anvaka@c-76-121-53-98.hsd1.wa.comcast.net] has quit [Remote
          host closed the connection]
22:54 -!- anvaka [~anvaka@2601:8:ac80:3f9:b104:906b:b936:4b9b] has joined
          #stackvm
23:01 -!- oldskirt_ [~oldskirt@unaffiliated/frodenius] has joined #stackvm
23:01 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          quit [Quit: ryan_stevens]
23:03 -!- oldskirt [~oldskirt@unaffiliated/frodenius] has quit [Ping timeout:
          255 seconds]
23:17 -!- pfraze [~pfraze@2605:6000:e900:d200:34ea:c44d:765e:9f78] has quit
          [Quit: Leaving]
23:24 -!- peutetre [~peutetre@46.115.181.18] has joined #stackvm
23:32 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has quit [Ping
          timeout: 244 seconds]
Day changed to 03 Nov 2014
00:16 -!- peutetre [~peutetre@46.115.181.18] has quit [Quit: peutetre]
00:17 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has quit [Quit: Computer has gone to sleep.]
00:32 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has joined
          #stackvm
          [Quit: Leaving]
23:24 -!- peutetre [~peutetre@46.115.181.18] has joined #stackvm
23:32 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has quit [Ping
          timeout: 244 seconds]
Day changed to 03 Nov 2014
00:16 -!- peutetre [~peutetre@46.115.181.18] has quit [Quit: peutetre]
00:17 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has quit [Quit: Computer has gone to sleep.]
00:32 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has joined
          #stackvm
00:35 -!- jxson [~jxson@c-98-210-181-134.hsd1.ca.comcast.net] has joined
          #stackvm
00:39 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has quit [Quit:
          dguttman]
00:57 -!- felixn [~felixn@216.151.13.73] has quit [Ping timeout: 244 seconds]
00:58 -!- felixn [~felixn@216.151.13.73] has joined #stackvm
01:02 -!- jxson [~jxson@c-98-210-181-134.hsd1.ca.comcast.net] has quit [Remote
          host closed the connection]
01:03 -!- jxson [~jxson@c-98-210-181-134.hsd1.ca.comcast.net] has joined
          #stackvm
01:07 -!- jxson [~jxson@c-98-210-181-134.hsd1.ca.comcast.net] has quit [Ping
          timeout: 255 seconds]
01:19 -!- jxson [~jxson@c-98-210-181-134.hsd1.ca.comcast.net] has joined
          #stackvm
01:48 -!- jxson [~jxson@c-98-210-181-134.hsd1.ca.comcast.net] has quit [Remote
          host closed the connection]
01:49 -!- jxson [~jxson@c-98-210-181-134.hsd1.ca.comcast.net] has joined
          #stackvm
01:53 -!- jxson [~jxson@c-98-210-181-134.hsd1.ca.comcast.net] has quit [Ping
          timeout: 264 seconds]
02:17 -!- stagas [~stagas@athedsl-4413812.home.otenet.gr] has joined #stackvm
02:32 -!- maxgfeller [~Thunderbi@46.140.66.34] has quit [Quit: maxgfeller]
02:34 -!- stagas [~stagas@athedsl-4413812.home.otenet.gr] has quit [Quit: Bye]
02:36 -!- maxgfeller [~Thunderbi@46.140.66.34] has joined #stackvm
02:44 -!- fotoverite [~fotoverit@cpe-67-243-154-113.nyc.res.rr.com] has quit
          [Quit: fotoverite]
02:45 < substack> https://github.com/substack/hyperboot
02:46 < substack> next I'll get the live demo working but not tonight
02:46 -!- kumavis__ [~kumavis@107-219-148-42.lightspeed.sntcca.sbcglobal.net]
          has quit [Ping timeout: 244 seconds]
02:52 -!- fotoverite [~fotoverit@cpe-67-243-154-113.nyc.res.rr.com] has joined
          #stackvm
03:11 -!- fotoverite [~fotoverit@cpe-67-243-154-113.nyc.res.rr.com] has quit
          [Quit: fotoverite]
03:15 -!- tixz [~tixz@2001:878:200:1053:4568:c91d:9965:afbe] has joined #stackvm
03:16 -!- fotoverite [~fotoverit@cpe-67-243-154-113.nyc.res.rr.com] has joined
          #stackvm
03:22 -!- tixz [~tixz@2001:878:200:1053:4568:c91d:9965:afbe] has quit [Remote
          host closed the connection]
03:23 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          joined #stackvm
03:26 -!- anvaka [~anvaka@2601:8:ac80:3f9:b104:906b:b936:4b9b] has quit [Remote
          host closed the connection]
03:27 -!- fotoverite [~fotoverit@cpe-67-243-154-113.nyc.res.rr.com] has quit
          [Quit: fotoverite]
03:33 -!- tixz [~tixz@2001:878:200:1053:553:fa62:b81c:24a6] has joined #stackvm
03:42 -!- tixz [~tixz@2001:878:200:1053:553:fa62:b81c:24a6] has quit [Remote
          host closed the connection]
03:45 -!- tixz [~tixz@130.225.93.167] has joined #stackvm
03:47 -!- tixz [~tixz@130.225.93.167] has quit [Remote host closed the
          connection]
04:10 -!- Mso150_n [~ctlM@80.83.239.116] has joined #stackvm
04:11 -!- Mso150 [~ctlM@80.83.239.84] has quit [Ping timeout: 255 seconds]
04:13 -!- kumavis_ [~kumavis@107-219-148-42.lightspeed.sntcca.sbcglobal.net]
          has joined #stackvm
04:17 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          quit [Remote host closed the connection]
04:18 -!- kumavis_ [~kumavis@107-219-148-42.lightspeed.sntcca.sbcglobal.net]
          has quit [Ping timeout: 245 seconds]
05:10 -!- djcoin [~djcoin@ip-125.net-89-2-68.rev.numericable.fr] has joined
          #stackvm
05:20 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          joined #stackvm
05:27 -!- anvaka [~anvaka@2601:8:ac80:3f9:b1b1:b15c:8f01:e38b] has joined
          #stackvm
05:32 -!- anvaka [~anvaka@2601:8:ac80:3f9:b1b1:b15c:8f01:e38b] has quit [Ping
          timeout: 272 seconds]
06:15 -!- Mso150_n [~ctlM@80.83.239.116] has quit [Ping timeout: 244 seconds]
06:16 -!- Mso150_n [~ctlM@80.83.239.83] has joined #stackvm
06:23 -!- Mso150_n [~ctlM@80.83.239.83] has quit [Read error: Connection reset
          by peer]
06:37 -!- insertcoffee [~insertcof@2.27.91.224] has joined #stackvm
06:42 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has joined
          #stackvm
06:47 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has quit [Ping
          timeout: 245 seconds]
06:50 -!- gorhgorh [~gorhgorh@175.229.207.77.rev.sfr.net] has joined #stackvm
07:00 -!- insertcoffee_mob
          [uid49819@gateway/web/irccloud.com/x-umafnwkvafeeikob] has quit
          [Quit: Connection closed for inactivity]
07:03 -!- tixz [~tixz@mac-kkri-324.imm.dtu.dk] has joined #stackvm
07:03 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has joined
          #stackvm
07:14 -!- _contrahax [~contrahax@ip24-251-13-101.ph.ph.cox.net] has quit [Quit:
          Sleeping]
07:21 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has quit
          [Ping timeout: 272 seconds]
07:27 -!- anvaka [~anvaka@2601:8:ac80:3f9:a07c:2b2b:d5fd:7c8d] has joined
          #stackvm
07:32 -!- anvaka [~anvaka@2601:8:ac80:3f9:a07c:2b2b:d5fd:7c8d] has quit [Ping
          timeout: 272 seconds]
07:32 -!- naneau [~naneau@unaffiliated/naneau] has joined #stackvm
07:36 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          quit [Remote host closed the connection]
07:46 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          joined #stackvm
07:51 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has joined
          #stackvm
07:54 -!- peutetre [~peutetre@62.129.6.2] has joined #stackvm
08:14 -!- peutetre [~peutetre@62.129.6.2] has quit [Quit: peutetre]
08:29 -!- peutetre [~peutetre@62.129.6.2] has joined #stackvm
08:30 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          quit [Remote host closed the connection]
08:32 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has quit
          [Ping timeout: 260 seconds]
08:38 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has joined
          #stackvm
08:40 -!- peutetre [~peutetre@62.129.6.2] has quit [Quit: peutetre]
08:50 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has quit
          [Ping timeout: 256 seconds]
08:51 -!- kriskowal [~kris@8.26.157.128] has quit [Ping timeout: 244 seconds]
08:56 -!- knownasilya [uid22190@gateway/web/irccloud.com/x-szlrrfxjdhvqcljs]
          has joined #stackvm
09:05 -!- peutetre [~peutetre@62.129.6.2] has joined #stackvm
09:14 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has joined
          #stackvm
09:19 -!- kriskowal [~kris@8.26.157.128] has joined #stackvm
09:26 -!- naneau [~naneau@unaffiliated/naneau] has quit [Quit: Quit.]
09:28 -!- naneau [~naneau@unaffiliated/naneau] has joined #stackvm
09:28 -!- anvaka [~anvaka@2601:8:ac80:3f9:2a:2d88:5d:bb42] has joined #stackvm
09:31 -!- domanic [~domanic@176-21-30-230-static.dk.customer.tdc.net] has
          joined #stackvm
09:33 -!- anvaka [~anvaka@2601:8:ac80:3f9:2a:2d88:5d:bb42] has quit [Ping
          timeout: 272 seconds]
09:33 -!- peutetre [~peutetre@62.129.6.2] has quit [Quit: peutetre]
09:41 < domanic> sorribas, yo! I am now geolocated in copenhagen!
09:43 < sorribas> domanic Awesome! I'm at work, and will be here until around
                  6pm. Maybe we can get together after that?
09:43 -!- naneau [~naneau@unaffiliated/naneau] has quit [Quit: Quit.]
09:43 < domanic> sorribas, yes - no problem, I'm just gonna hack from this cafe
                 for a bit
09:45 < sorribas> domanic cool! I'll comunicate through IRC or twitter.
09:49 < domanic> sorribas, sweet
09:54 -!- cpup [~CoderPupp@32.218.117.151] has quit [Read error: Connection
          reset by peer]
09:56 -!- cpup [~CoderPupp@32.218.117.151] has joined #stackvm
09:56 -!- naneau [~naneau@unaffiliated/naneau] has joined #stackvm
09:57 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has joined
          #stackvm
10:05 -!- tixz [~tixz@mac-kkri-324.imm.dtu.dk] has quit [Remote host closed the
          connection]
10:12 -!- kumavis_ [~kumavis@107-219-148-42.lightspeed.sntcca.sbcglobal.net]
          has joined #stackvm
10:16 -!- robertkowalski [robert@apache/committer/robertkowalski] has joined
          #stackvm
10:17 -!- kumavis_ [~kumavis@107-219-148-42.lightspeed.sntcca.sbcglobal.net]
          has quit [Ping timeout: 256 seconds]
10:18 -!- kriskowal [~kris@8.26.157.128] has quit [Ping timeout: 245 seconds]
10:28 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has joined #stackvm
10:30 -!- fotoverite [~fotoverit@cpe-67-243-154-113.nyc.res.rr.com] has joined
          #stackvm
10:30 -!- pfraze [~pfraze@2605:6000:e900:d200:35b3:1765:3f06:bd8b] has joined
          #stackvm
10:34 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          joined #stackvm
10:39 -!- kriskowal [~kris@8.26.157.128] has joined #stackvm
10:40 -!- j0hn_ [~JohnDotAw@216.201.168.18] has joined #stackvm
10:51 -!- toddself [~toddself@pool-173-68-17-221.pghkny.fios.verizon.net] has
          joined #stackvm
11:05 -!- peutetre [~peutetre@62.129.6.2] has joined #stackvm
11:17 -!- ednapiranha [~ednapiran@207.126.102.129] has joined #stackvm
11:29 -!- anvaka [~anvaka@2601:8:ac80:3f9:9888:2230:ee1e:86a5] has joined
          #stackvm
11:34 -!- anvaka [~anvaka@2601:8:ac80:3f9:9888:2230:ee1e:86a5] has quit [Ping
          timeout: 272 seconds]
11:36 -!- shama [~shama@2601:7:1b80:397:2dd6:9507:5e62:5e57] has joined #stackvm
11:42 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has quit
          [Ping timeout: 255 seconds]
11:46 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has quit [Quit:
          dguttman]
11:47 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has joined
          #stackvm
11:47 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has joined
          #stackvm
12:04 -!- jxson [jxson@nat/google/x-ftxhlfwguaombkqj] has joined #stackvm
12:06 -!- naneau [~naneau@unaffiliated/naneau] has quit [Quit: Part.]
12:06 -!- kumavis_ [~kumavis@107-219-148-42.lightspeed.sntcca.sbcglobal.net]
          has joined #stackvm
12:07 -!- domanic [~domanic@176-21-30-230-static.dk.customer.tdc.net] has quit
          [Ping timeout: 244 seconds]
12:17 -!- toddself is now known as toddself_zz
12:26 -!- peutetre [~peutetre@62.129.6.2] has quit [Quit: peutetre]
12:40 -!- djcoin [~djcoin@ip-125.net-89-2-68.rev.numericable.fr] has quit
          [Quit: WeeChat 1.0]
12:40 -!- anvaka [~anvaka@2601:8:ac80:3f9:a856:65b8:e22b:28b9] has joined
          #stackvm
12:42 -!- toddself_zz is now known as toddself
12:45 < sorribas> Hey man. Where are you?
12:49 -!- gangleri [~gangleri@178.250.114.154] has joined #stackvm
12:53 -!- jxson_ [jxson@nat/google/x-hsidwtthzepdybtu] has joined #stackvm
12:56 -!- jxson [jxson@nat/google/x-ftxhlfwguaombkqj] has quit [Ping timeout:
          265 seconds]
13:07 -!- kumavis_ [~kumavis@107-219-148-42.lightspeed.sntcca.sbcglobal.net]
          has quit [Ping timeout: 255 seconds]
13:08 -!- peutetre [~peutetre@195.101.111.125] has joined #stackvm
13:11 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has quit [Quit: Computer has gone to sleep.]
13:20 -!- kumavis_ [~kumavis@107-219-148-42.lightspeed.sntcca.sbcglobal.net]
          has joined #stackvm
13:21 -!- warbrett [~warbrett@wsip-70-166-103-182.ph.ph.cox.net] has joined
          #stackvm
13:22 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has joined #stackvm
13:27 -!- oldskirt [~oldskirt@unaffiliated/frodenius] has joined #stackvm
13:28 -!- anvaka [~anvaka@2601:8:ac80:3f9:a856:65b8:e22b:28b9] has quit [Remote
          host closed the connection]
13:29 -!- gangleri [~gangleri@178.250.114.154] has quit [Ping timeout: 256
          seconds]
13:29 -!- oldskirt_ [~oldskirt@unaffiliated/frodenius] has quit [Ping timeout:
          255 seconds]
13:34 -!- peutetre [~peutetre@195.101.111.125] has quit [Quit: peutetre]
13:36 -!- gozala [uid5923@gateway/web/irccloud.com/x-hzxgwggjxhydbqku] has
          joined #stackvm
13:37 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has quit
          [Ping timeout: 264 seconds]
13:39 -!- kessler [~kessler@109.226.21.81] has joined #stackvm
13:41 -!- Ursium [~Ursium@cpc2-mort5-2-0-cust245.croy.cable.virginm.net] has
          quit [Quit: AFK]
13:41 -!- stagas [~stagas@athedsl-4413812.home.otenet.gr] has joined #stackvm
13:42 -!- Ursium [~Ursium@cpc2-mort5-2-0-cust245.croy.cable.virginm.net] has
          joined #stackvm
13:42 -!- tilgovi [~randall@couchdb/committer/tilgovi] has joined #stackvm
13:49 -!- kessler_ [~kessler@odap-199-203-61-108.bb.netvision.net.il] has
          joined #stackvm
13:50 -!- kessler [~kessler@109.226.21.81] has quit [Ping timeout: 255 seconds]
14:01 -!- yorick [~yorick@oftn/member/yorick] has quit [Quit: No Ping reply in
          180 seconds.]
14:03 -!- yorick [~yorick@oftn/member/yorick] has joined #stackvm
14:18 -!- kumavis_ [~kumavis@107-219-148-42.lightspeed.sntcca.sbcglobal.net]
          has quit [Quit: Textual IRC Client: www.textualapp.com]
14:36 -!- kessler_ [~kessler@odap-199-203-61-108.bb.netvision.net.il] has quit
          [Ping timeout: 272 seconds]
14:36 -!- phated_ [~phated@m874636d0.tmodns.net] has joined #stackvm
14:44 -!- toddself is now known as toddself_zz
14:51 -!- rockbot__ [~rockbot__@76.102.192.246] has joined #stackvm
14:57 -!- Mso150 [~ctlM@80.83.239.95] has joined #stackvm
15:04 -!- toddself_zz is now known as toddself
15:09 -!- jxson_ [jxson@nat/google/x-hsidwtthzepdybtu] has quit [Remote host
          closed the connection]
15:10 -!- jxson [~jxson@216.239.45.80] has joined #stackvm
15:13 -!- jxson [~jxson@216.239.45.80] has quit [Remote host closed the
          connection]
15:16 -!- rockbot__ [~rockbot__@76.102.192.246] has quit [Remote host closed
          the connection]
15:17 -!- rockbot__ [~rockbot__@76.102.192.246] has joined #stackvm
15:23 -!- jxson [jxson@nat/google/x-wmfpztjvgnsimuml] has joined #stackvm
15:24 -!- phated__ [~phated@wsip-70-166-103-182.ph.ph.cox.net] has joined
          #stackvm
15:24 -!- phated__ is now known as phated
15:25 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has joined
          #stackvm
15:25 -!- phated_ [~phated@m874636d0.tmodns.net] has quit [Ping timeout: 265
          seconds]
15:26 -!- toddself [~toddself@pool-173-68-17-221.pghkny.fios.verizon.net] has
          quit []
15:35 -!- rockbot__ [~rockbot__@76.102.192.246] has quit [Remote host closed
          the connection]
15:35 -!- jxson [jxson@nat/google/x-wmfpztjvgnsimuml] has quit [Remote host
          closed the connection]
15:45 < substack> http://demo.hyperboot.org/
15:50 -!- kessler [~kessler@odap-199-203-61-108.bb.netvision.net.il] has quit
          [Ping timeout: 244 seconds]
15:52 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has quit [Quit: Computer has gone to sleep.]
15:59 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has joined #stackvm
16:03 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          joined #stackvm
16:07 -!- Mso150_z [~ctlM@80.83.238.73] has joined #stackvm
16:07 -!- Mso150 [~ctlM@80.83.239.95] has quit [Ping timeout: 265 seconds]
16:07 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          quit [Ping timeout: 265 seconds]
16:09 -!- jxson [~jxson@216.239.45.92] has joined #stackvm
16:10 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          joined #stackvm
16:16 -!- tixz [~tixz@94.191.189.11.bredband.3.dk] has joined #stackvm
16:22 -!- tixz [~tixz@94.191.189.11.bredband.3.dk] has quit [Ping timeout: 255
          seconds]
16:22 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has quit [Quit: Computer has gone to sleep.]
16:28 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          quit [Remote host closed the connection]
16:32 -!- tixz [~tixz@82.211.209.116] has joined #stackvm
16:36 -!- rockbot__ [~rockbot__@76.102.192.246] has joined #stackvm
16:38 -!- kessler [~kessler@109.253.106.227] has joined #stackvm
16:39 -!- rockbot__ [~rockbot__@76.102.192.246] has quit [Remote host closed
          the connection]
16:40 -!- rockbot__ [~rockbot__@76.102.192.246] has joined #stackvm
16:41 -!- ceejbot [~ceejbot@76.102.192.246] has joined #stackvm
16:44 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          joined #stackvm
16:47 -!- tixz [~tixz@82.211.209.116] has quit [Remote host closed the
          connection]
16:49 -!- tixz [~tixz@82.211.209.116] has joined #stackvm
16:50 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          quit [Remote host closed the connection]
16:51 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          joined #stackvm
16:54 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has joined #stackvm
17:01 -!- pfraze [~pfraze@2605:6000:e900:d200:35b3:1765:3f06:bd8b] has quit
          [Quit: Leaving]
17:06 -!- insertcoffee [~insertcof@2.27.91.224] has quit [Remote host closed
          the connection]
17:11 < ogd> https://www.youtube.com/watch?v=ggCffvKEJmQ
17:14 -!- toddself [~toddself@pool-173-68-17-221.pghkny.fios.verizon.net] has
          joined #stackvm
17:27 -!- ceejbot_ [~ceejbot@50-0-146-104.dsl.dynamic.fusionbroadband.com] has
          joined #stackvm
17:30 -!- rockbo___ [~rockbot__@50-0-146-104.dsl.dynamic.fusionbroadband.com]
          has joined #stackvm
17:30 -!- ceejbot [~ceejbot@76.102.192.246] has quit [Ping timeout: 265 seconds]
17:31 < terinjokes> ogd: can you pretty please merge my element-class change? :D
17:33 -!- rockbot__ [~rockbot__@76.102.192.246] has quit [Ping timeout: 255
          seconds]
17:49 -!- tilgovi [~randall@couchdb/committer/tilgovi] has quit [Ping timeout:
          244 seconds]
17:53 -!- kessler [~kessler@109.253.106.227] has quit [Ping timeout: 250
          seconds]
17:55 -!- jxson__ [jxson@nat/google/x-aqfkquhdxbuedanr] has joined #stackvm
17:56 -!- jxson [~jxson@216.239.45.92] has quit [Ping timeout: 256 seconds]
18:00 -!- tilgovi [~randall@couchdb/committer/tilgovi] has joined #stackvm
18:05 -!- tixz [~tixz@82.211.209.116] has quit [Remote host closed the
          connection]
18:06 -!- rockbo___ is now known as rockbot__
18:12 -!- toddself is now known as toddself_zz
18:26 -!- pfraze [~pfraze@2605:6000:e900:d200:8b7:8612:2a51:502a] has joined
          #stackvm
18:27 -!- contrahax [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has joined
          #stackvm
18:31 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          quit [Remote host closed the connection]
18:34 < owen1> http://youtu.be/KSdNYi55kjg?list=UUWEm1sjdZrdd2_n4wGRw5fw the
               fastest talk from RICON
18:39 -!- oncenull [~pose@190.194.140.191] has joined #stackvm
18:42 -!- oncenull [~pose@190.194.140.191] has quit [Client Quit]
18:42 -!- oncenull [~pose@190.194.140.191] has joined #stackvm
18:44 -!- oncenull [~pose@190.194.140.191] has quit [Client Quit]
18:46 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has quit [Quit: Computer has gone to sleep.]
18:46 -!- jxson__ [jxson@nat/google/x-aqfkquhdxbuedanr] has quit [Remote host
          closed the connection]
18:48 -!- jxson [jxson@nat/google/x-ykhoprboermijlmn] has joined #stackvm
19:00 -!- ircretary [~ircretary@165.225.132.207] has quit [Remote host closed
          the connection]
19:00 -!- ircretary [~ircretary@165.225.132.207] has joined #stackvm
19:02 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has joined
          #stackvm
19:03 -!- tilgovi [~randall@couchdb/committer/tilgovi] has quit [Remote host
          closed the connection]
19:05 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has joined #stackvm
19:13 -!- gorhgorh [~gorhgorh@175.229.207.77.rev.sfr.net] has quit [Quit:
          gorhgorh]
19:14 -!- thlorenz [~thlorenz@1.132.201.56] has joined #stackvm
19:24 -!- thlorenz_ [~thlorenz@1.132.201.56] has joined #stackvm
19:24 -!- thlorenz [~thlorenz@1.132.201.56] has quit [Read error: Connection
          reset by peer]
19:25 -!- ednapiranha [~ednapiran@207.126.102.129] has quit [Quit: Leaving...]
19:28 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has quit [Quit: Computer has gone to sleep.]
19:29 -!- knownasilya [uid22190@gateway/web/irccloud.com/x-szlrrfxjdhvqcljs]
          has quit [Quit: Connection closed for inactivity]
19:42 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          quit [Quit: ryan_stevens]
19:45 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          joined #stackvm
19:49 -!- contrahax is now known as _contrahax
19:49 -!- _contrahax is now known as contrahax
20:06 -!- stagas [~stagas@athedsl-4413812.home.otenet.gr] has quit [Ping
          timeout: 265 seconds]
20:20 -!- rockbot__ [~rockbot__@50-0-146-104.dsl.dynamic.fusionbroadband.com]
          has quit [Remote host closed the connection]
20:21 -!- knownasilya [uid22190@gateway/web/irccloud.com/x-sriatomdrhhqydut]
          has joined #stackvm
20:32 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Remote host closed the connection]
20:32 -!- toddself_zz is now known as toddself
20:32 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has quit [Ping
          timeout: 256 seconds]
20:33 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
20:35 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has joined
          #stackvm
20:37 -!- toddself [~toddself@pool-173-68-17-221.pghkny.fios.verizon.net] has
          quit []
20:41 -!- warbrett [~warbrett@wsip-70-166-103-182.ph.ph.cox.net] has quit
          [Remote host closed the connection]
20:43 -!- jxson_ [jxson@nat/google/x-jqbhydykiintyzsn] has joined #stackvm
20:47 -!- jxson [jxson@nat/google/x-ykhoprboermijlmn] has quit [Ping timeout:
          272 seconds]
20:53 -!- rockbot__ [~rockbot__@76.102.192.246] has joined #stackvm
20:59 -!- kriskowal [~kris@8.26.157.128] has quit [Quit: kriskowal]
20:59 -!- contraha_ [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has joined
          #stackvm
21:00 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          quit [Quit: ryan_stevens]
21:01 -!- contrahax [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has quit
          [Ping timeout: 255 seconds]
21:02 -!- rockbot__ [~rockbot__@76.102.192.246] has quit [Remote host closed
          the connection]
21:02 -!- ceejbot_ [~ceejbot@50-0-146-104.dsl.dynamic.fusionbroadband.com] has
          quit [Remote host closed the connection]
21:03 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Remote host closed the connection]
21:06 -!- tixz [~tixz@82.211.209.116] has joined #stackvm
21:06 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          joined #stackvm
21:10 -!- tixz [~tixz@82.211.209.116] has quit [Ping timeout: 250 seconds]
21:49 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has quit [Ping
          timeout: 250 seconds]
21:52 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has joined
          #stackvm
21:57 -!- thlorenz_ [~thlorenz@1.132.201.56] has quit [Remote host closed the
          connection]
21:59 -!- jxson_ [jxson@nat/google/x-jqbhydykiintyzsn] has quit [Remote host
          closed the connection]
21:59 -!- thlorenz [~thlorenz@1.132.201.56] has joined #stackvm
22:04 -!- thlorenz [~thlorenz@1.132.201.56] has quit [Ping timeout: 260 seconds]
22:25 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
22:32 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 255 seconds]
22:46 -!- thlorenz [~thlorenz@1.132.201.56] has joined #stackvm
22:49 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has quit [Ping
          timeout: 240 seconds]
22:53 -!- ceejbot [~ceejbot@172-5-154-148.lightspeed.sntcca.sbcglobal.net] has
          joined #stackvm
23:07 -!- contrahax [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has joined
          #stackvm
23:07 -!- contraha_ [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has quit
          [Ping timeout: 244 seconds]
23:16 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
23:21 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 256 seconds]
23:26 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
23:27 -!- phated [~phated@wsip-70-166-103-182.ph.ph.cox.net] has quit [Remote
          host closed the connection]
23:31 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 255 seconds]
23:36 -!- anvaka [~anvaka@216.243.14.45] has joined #stackvm
23:43 -!- contrahax [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has quit
          [Quit: Sleeping]
23:52 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
23:54 -!- rockbot__ [~rockbot__@c-98-207-60-247.hsd1.ca.comcast.net] has joined
          #stackvm
23:56 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 256 seconds]
Day changed to 04 Nov 2014
00:04 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has quit [Quit:
          dguttman]
00:05 -!- thlorenz_ [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          joined #stackvm
00:10 -!- thlorenz [~thlorenz@1.132.201.56] has quit [Ping timeout: 272 seconds]
00:15 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has joined
          #stackvm
17:30 -!- rockbo___ [~rockbot__@50-0-146-104.dsl.dynamic.fusionbroadband.com]
          has joined #stackvm
17:30 -!- ceejbot [~ceejbot@76.102.192.246] has quit [Ping timeout: 265 seconds]
17:31 < terinjokes> ogd: can you pretty please merge my element-class change? :D
17:33 -!- rockbot__ [~rockbot__@76.102.192.246] has quit [Ping timeout: 255
          seconds]
17:49 -!- tilgovi [~randall@couchdb/committer/tilgovi] has quit [Ping timeout:
          244 seconds]
17:53 -!- kessler [~kessler@109.253.106.227] has quit [Ping timeout: 250
          seconds]
16:44 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          joined #stackvm
16:47 -!- tixz [~tixz@82.211.209.116] has quit [Remote host closed the
          connection]
16:49 -!- tixz [~tixz@82.211.209.116] has joined #stackvm
16:50 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          quit [Remote host closed the connection]
16:51 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          joined #stackvm
16:54 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has joined #stackvm
17:01 -!- pfraze [~pfraze@2605:6000:e900:d200:35b3:1765:3f06:bd8b] has quit
          [Quit: Leaving]
17:06 -!- insertcoffee [~insertcof@2.27.91.224] has quit [Remote host closed
          the connection]
17:11 < ogd> https://www.youtube.com/watch?v=ggCffvKEJmQ
17:14 -!- toddself [~toddself@pool-173-68-17-221.pghkny.fios.verizon.net] has
          joined #stackvm
17:27 -!- ceejbot_ [~ceejbot@50-0-146-104.dsl.dynamic.fusionbroadband.com] has
          joined #stackvm
17:30 -!- rockbo___ [~rockbot__@50-0-146-104.dsl.dynamic.fusionbroadband.com]
          has joined #stackvm
17:30 -!- ceejbot [~ceejbot@76.102.192.246] has quit [Ping timeout: 265 seconds]
17:31 < terinjokes> ogd: can you pretty please merge my element-class change? :D
17:33 -!- rockbot__ [~rockbot__@76.102.192.246] has quit [Ping timeout: 255
          seconds]
17:49 -!- tilgovi [~randall@couchdb/committer/tilgovi] has quit [Ping timeout:
          244 seconds]
17:53 -!- kessler [~kessler@109.253.106.227] has quit [Ping timeout: 250
          seconds]
17:55 -!- jxson__ [jxson@nat/google/x-aqfkquhdxbuedanr] has joined #stackvm
17:56 -!- jxson [~jxson@216.239.45.92] has quit [Ping timeout: 256 seconds]
18:00 -!- tilgovi [~randall@couchdb/committer/tilgovi] has joined #stackvm
18:05 -!- tixz [~tixz@82.211.209.116] has quit [Remote host closed the
          connection]
18:06 -!- rockbo___ is now known as rockbot__
18:12 -!- toddself is now known as toddself_zz
18:26 -!- pfraze [~pfraze@2605:6000:e900:d200:8b7:8612:2a51:502a] has joined
          #stackvm
18:27 -!- contrahax [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has joined
          #stackvm
18:31 -!- thlorenz [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          quit [Remote host closed the connection]
18:34 < owen1> http://youtu.be/KSdNYi55kjg?list=UUWEm1sjdZrdd2_n4wGRw5fw the
               fastest talk from RICON
18:39 -!- oncenull [~pose@190.194.140.191] has joined #stackvm
18:42 -!- oncenull [~pose@190.194.140.191] has quit [Client Quit]
18:42 -!- oncenull [~pose@190.194.140.191] has joined #stackvm
18:44 -!- oncenull [~pose@190.194.140.191] has quit [Client Quit]
18:46 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has quit [Quit: Computer has gone to sleep.]
18:46 -!- jxson__ [jxson@nat/google/x-aqfkquhdxbuedanr] has quit [Remote host
          closed the connection]
18:48 -!- jxson [jxson@nat/google/x-ykhoprboermijlmn] has joined #stackvm
19:00 -!- ircretary [~ircretary@165.225.132.207] has quit [Remote host closed
          the connection]
19:00 -!- ircretary [~ircretary@165.225.132.207] has joined #stackvm
19:02 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has joined
          #stackvm
19:03 -!- tilgovi [~randall@couchdb/committer/tilgovi] has quit [Remote host
          closed the connection]
19:05 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has joined #stackvm
19:13 -!- gorhgorh [~gorhgorh@175.229.207.77.rev.sfr.net] has quit [Quit:
          gorhgorh]
19:14 -!- thlorenz [~thlorenz@1.132.201.56] has joined #stackvm
19:24 -!- thlorenz_ [~thlorenz@1.132.201.56] has joined #stackvm
19:24 -!- thlorenz [~thlorenz@1.132.201.56] has quit [Read error: Connection
          reset by peer]
19:25 -!- ednapiranha [~ednapiran@207.126.102.129] has quit [Quit: Leaving...]
19:28 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has quit [Quit: Computer has gone to sleep.]
19:29 -!- knownasilya [uid22190@gateway/web/irccloud.com/x-szlrrfxjdhvqcljs]
          has quit [Quit: Connection closed for inactivity]
19:42 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          quit [Quit: ryan_stevens]
19:45 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          joined #stackvm
19:49 -!- contrahax is now known as _contrahax
19:49 -!- _contrahax is now known as contrahax
20:06 -!- stagas [~stagas@athedsl-4413812.home.otenet.gr] has quit [Ping
          timeout: 265 seconds]
20:20 -!- rockbot__ [~rockbot__@50-0-146-104.dsl.dynamic.fusionbroadband.com]
          has quit [Remote host closed the connection]
20:21 -!- knownasilya [uid22190@gateway/web/irccloud.com/x-sriatomdrhhqydut]
          has joined #stackvm
20:32 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Remote host closed the connection]
20:32 -!- toddself_zz is now known as toddself
20:32 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has quit [Ping
          timeout: 256 seconds]
20:33 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
20:35 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has joined
          #stackvm
20:37 -!- toddself [~toddself@pool-173-68-17-221.pghkny.fios.verizon.net] has
          quit []
20:41 -!- warbrett [~warbrett@wsip-70-166-103-182.ph.ph.cox.net] has quit
          [Remote host closed the connection]
20:43 -!- jxson_ [jxson@nat/google/x-jqbhydykiintyzsn] has joined #stackvm
20:47 -!- jxson [jxson@nat/google/x-ykhoprboermijlmn] has quit [Ping timeout:
          272 seconds]
20:53 -!- rockbot__ [~rockbot__@76.102.192.246] has joined #stackvm
20:59 -!- kriskowal [~kris@8.26.157.128] has quit [Quit: kriskowal]
20:59 -!- contraha_ [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has joined
          #stackvm
21:00 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          quit [Quit: ryan_stevens]
21:01 -!- contrahax [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has quit
          [Ping timeout: 255 seconds]
21:02 -!- rockbot__ [~rockbot__@76.102.192.246] has quit [Remote host closed
          the connection]
21:02 -!- ceejbot_ [~ceejbot@50-0-146-104.dsl.dynamic.fusionbroadband.com] has
          quit [Remote host closed the connection]
21:03 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Remote host closed the connection]
21:06 -!- tixz [~tixz@82.211.209.116] has joined #stackvm
21:06 -!- ryan_stevens [~ryan_stev@c-50-174-131-239.hsd1.ca.comcast.net] has
          joined #stackvm
21:10 -!- tixz [~tixz@82.211.209.116] has quit [Ping timeout: 250 seconds]
21:49 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has quit [Ping
          timeout: 250 seconds]
21:52 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has joined
          #stackvm
21:57 -!- thlorenz_ [~thlorenz@1.132.201.56] has quit [Remote host closed the
          connection]
21:59 -!- jxson_ [jxson@nat/google/x-jqbhydykiintyzsn] has quit [Remote host
          closed the connection]
21:59 -!- thlorenz [~thlorenz@1.132.201.56] has joined #stackvm
22:04 -!- thlorenz [~thlorenz@1.132.201.56] has quit [Ping timeout: 260 seconds]
22:25 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
22:32 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 255 seconds]
22:46 -!- thlorenz [~thlorenz@1.132.201.56] has joined #stackvm
22:49 -!- kessler [~kessler@bzq-80-62-132.static.bezeqint.net] has quit [Ping
          timeout: 240 seconds]
22:53 -!- ceejbot [~ceejbot@172-5-154-148.lightspeed.sntcca.sbcglobal.net] has
          joined #stackvm
23:07 -!- contrahax [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has joined
          #stackvm
23:07 -!- contraha_ [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has quit
          [Ping timeout: 244 seconds]
23:16 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
23:21 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 256 seconds]
23:26 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
23:27 -!- phated [~phated@wsip-70-166-103-182.ph.ph.cox.net] has quit [Remote
          host closed the connection]
23:31 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 255 seconds]
23:36 -!- anvaka [~anvaka@216.243.14.45] has joined #stackvm
23:43 -!- contrahax [~contrahax@wsip-70-166-121-220.ph.ph.cox.net] has quit
          [Quit: Sleeping]
23:52 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
23:54 -!- rockbot__ [~rockbot__@c-98-207-60-247.hsd1.ca.comcast.net] has joined
          #stackvm
23:56 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 256 seconds]
Day changed to 04 Nov 2014
00:04 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has quit [Quit:
          dguttman]
00:05 -!- thlorenz_ [~thlorenz@CPE-1-120-194-102.qcl9.cha.bigpond.net.au] has
          joined #stackvm
00:10 -!- thlorenz [~thlorenz@1.132.201.56] has quit [Ping timeout: 272 seconds]
00:15 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has joined
          #stackvm
00:18 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has quit [Read
          error: No route to host]
00:19 -!- dguttman [~david@cpe-104-173-91-255.socal.res.rr.com] has joined
          #stackvm
00:26 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
00:29 -!- knownasilya [uid22190@gateway/web/irccloud.com/x-sriatomdrhhqydut]
          has quit [Quit: Connection closed for inactivity]
00:31 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 264 seconds]
00:32 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
00:33 -!- phated [~phated@ip72-208-140-83.ph.ph.cox.net] has joined #stackvm
00:36 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 265 seconds]
00:45 -!- thealphanerd [~thealphan@pdpc/supporter/student/thealphanerd] has
          joined #stackvm
00:52 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
00:56 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 245 seconds]
00:59 -!- anvaka [~anvaka@216.243.14.45] has quit [Remote host closed the
          connection]
01:00 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
01:03 -!- rockbot__ [~rockbot__@c-98-207-60-247.hsd1.ca.comcast.net] has quit
          [Remote host closed the connection]
01:04 -!- rockbot__ [~rockbot__@c-98-207-60-247.hsd1.ca.comcast.net] has joined
          #stackvm
01:05 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 264 seconds]
01:10 -!- ceejbot [~ceejbot@172-5-154-148.lightspeed.sntcca.sbcglobal.net] has
          quit [Remote host closed the connection]
01:11 -!- ceejbot [~ceejbot@172-5-154-148.lightspeed.sntcca.sbcglobal.net] has
          joined #stackvm
01:11 -!- contrahax [~contrahax@ip24-251-13-101.ph.ph.cox.net] has joined
          #stackvm
01:13 -!- CoderPuppy [~CoderPupp@32.218.117.151] has joined #stackvm
01:15 -!- ceejbot [~ceejbot@172-5-154-148.lightspeed.sntcca.sbcglobal.net] has
          quit [Ping timeout: 250 seconds]
01:17 -!- n3b_ [~n3b@198.167.142.150] has joined #stackvm
01:17 -!- dlmanning_ [~dlmanning@162.243.218.8] has joined #stackvm
01:18 -!- Netsplit *.net <-> *.split quits: cpup, dlmanning, rockbot__, n3b
01:18 -!- dlmanning_ is now known as dlmanning
01:26 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
01:28 -!- phated [~phated@ip72-208-140-83.ph.ph.cox.net] has quit [Remote host
          closed the connection]
01:30 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 240 seconds]
01:30 -!- thealphanerd [~thealphan@pdpc/supporter/student/thealphanerd] has
          quit [Quit: thealphanerd]
02:05 -!- Netsplit over, joins: rockbot__
02:09 -!- rockbot__ [~rockbot__@c-98-207-60-247.hsd1.ca.comcast.net] has quit
          [Ping timeout: 244 seconds]
02:15 -!- contrahax is now known as _contrahax
02:20 -!- shama [~shama@2601:7:1b80:397:2dd6:9507:5e62:5e57] has quit [Quit:
          closed the connection]
01:30 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 240 seconds]
01:30 -!- thealphanerd [~thealphan@pdpc/supporter/student/thealphanerd] has
          quit [Quit: thealphanerd]
02:05 -!- Netsplit over, joins: rockbot__
02:09 -!- rockbot__ [~rockbot__@c-98-207-60-247.hsd1.ca.comcast.net] has quit
          [Ping timeout: 244 seconds]
02:15 -!- contrahax is now known as _contrahax
02:20 -!- shama [~shama@2601:7:1b80:397:2dd6:9507:5e62:5e57] has quit [Quit:
          (o°¡°	ÿo5ÿPoPes]
02:26 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
17:49 -!- tilgovi [~randall@couchdb/committer/tilgovi] has quit [Ping timeout:
          244 seconds]
18:00 -!- tilgovi [~randall@couchdb/committer/tilgovi] has joined #nerdtracker
18:16 -!- sirialize [~fenny@50-115-70-150.static-ip.telepacific.net] has quit
          [Quit: Leaving.]
18:18 -!- sirialize [~fenny@50-115-70-150.static-ip.telepacific.net] has joined
          #nerdtracker
18:20 -!- sirialize [~fenny@50-115-70-150.static-ip.telepacific.net] has quit
          [Client Quit]
18:27 -!- sirialize [~fenny@50-115-70-150.static-ip.telepacific.net] has joined
          #nerdtracker
18:32 -!- sirialize [~fenny@50-115-70-150.static-ip.telepacific.net] has quit
          [Ping timeout: 245 seconds]
18:38 -!- sirialize [~fenny@50-115-70-150.static-ip.telepacific.net] has joined
          #nerdtracker
18:46 -!- brianloveswords [~brianlove@pool-100-2-12-3.nycmny.fios.verizon.net]
          has quit [Quit: Computer has gone to sleep.]
19:00 -!- ircretary [~ircretary@165.225.132.207] has quit [Remote host closed
          the connection]
19:00 -!- ircretary [~ircretary@165.225.132.207] has joined #nerdtracker
02:42 -!- phated [~phated@ip72-208-140-83.ph.ph.cox.net] has quit [Read error:
          Connection reset by peer]
18:05 -!- tixz [~tixz@82.211.209.116] has quit [Remote host closed the
          connection]
18:07 -!- woah [~woah@75-101-111-82.dedicated.static.sonic.net] has quit [Quit:
          My MacBook Pro has gone to sleep. ZZZzzz&]
18:22 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has
          joined #scuttlebutt
18:26 -!- pfraze [~pfraze@2605:6000:e900:d200:8b7:8612:2a51:502a] has joined
          #scuttlebutt
19:06 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has quit
          [Remote host closed the connection]
19:07 < pfraze> need opinions on https://github.com/pfraze/phoenix/pull/135
19:25 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has
          joined #scuttlebutt
19:25 -!- ednapiranha [~ednapiran@207.126.102.129] has quit [Quit: Leaving...]
20:04 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has quit
          [Remote host closed the connection]
20:20 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has
          joined #scuttlebutt
20:33 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has quit
          [Remote host closed the connection]
20:45 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has
15:55 < pfraze> woah, yeah I've had my eye on that
15:56 < pfraze> so barring something like chromify, we might look into making
                websockets a common interface
15:58 < woah> browser-to-browser?
15:58 < pfraze> webrtc
15:59 < pfraze> or tunnels
15:59 < woah> ah, just with a wrapper to expose the same api?
15:59 < pfraze> yeah. It's pretty easy to make muxrpc (the rpc protocol and
                lib) work on any tcp-like channel
15:59 < substack> just pushed an update to the hyperboot demo, refresh and see
                  it in the update list!
16:00 < woah> nice, i'm definitely going to have to learn more about muxrpc
16:00 < pfraze> substack, works great
16:01 < woah> yep
16:01 < pfraze> the one weird thing is that I get a persistent loading spinner
                on the tab
16:01 < pfraze> this is FF on latest ubutnu
16:01 < pfraze> ubotnick
16:02 < substack> oh strange
16:03 < pfraze> let me check for clues...
16:03 < substack> pfraze: yeah I get the same thing with the spinny loader
16:03 < substack> on firefox but not on chrome
16:04 < pfraze> ok
16:04 < pfraze> yeah no signs about what that could be from the inspector
16:08 < pfraze> oh man I am so glad I added js/css autobuilding to the server
16:16 -!- tixz [~tixz@94.191.189.11.bredband.3.dk] has joined #scuttlebutt
16:21 < woah> easier to deal with?
16:22 < pfraze> yeah, less mental load
16:22 -!- tixz [~tixz@94.191.189.11.bredband.3.dk] has quit [Ping timeout: 255
          seconds]
16:32 -!- tixz [~tixz@82.211.209.116] has joined #scuttlebutt
16:34 < woah> too bad, looks like javascript is coming to an end
16:34 < woah> http://www.nomorejavascript.com/
16:36 < pfraze> I know, I was just getting good at it too
16:37 < woah> had a good run i guess
16:37 < pfraze> if only it didnt have that camel case
16:38 < pfraze> penny for thoughts: https://github.com/pfraze/phoenix/pull/133
                vs https://github.com/pfraze/phoenix/pull/134
16:39 < woah> definitely 134
16:39 < pfraze> I think so too
16:47 -!- tixz [~tixz@82.211.209.116] has quit [Remote host closed the
          connection]
16:49 -!- tixz [~tixz@82.211.209.116] has joined #scuttlebutt
17:01 -!- pfraze [~pfraze@2605:6000:e900:d200:35b3:1765:3f06:bd8b] has quit
          [Quit: Leaving]
17:55 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has
          joined #scuttlebutt
18:05 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has quit
          [Remote host closed the connection]
18:05 -!- tixz [~tixz@82.211.209.116] has quit [Remote host closed the
          connection]
18:07 -!- woah [~woah@75-101-111-82.dedicated.static.sonic.net] has quit [Quit:
          My MacBook Pro has gone to sleep. ZZZzzz&]
18:22 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has
          joined #scuttlebutt
18:26 -!- pfraze [~pfraze@2605:6000:e900:d200:8b7:8612:2a51:502a] has joined
          #scuttlebutt
19:06 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has quit
          [Remote host closed the connection]
19:07 < pfraze> need opinions on https://github.com/pfraze/phoenix/pull/135
19:25 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has
          joined #scuttlebutt
19:25 -!- ednapiranha [~ednapiran@207.126.102.129] has quit [Quit: Leaving...]
20:04 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has quit
          [Remote host closed the connection]
20:20 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has
          joined #scuttlebutt
20:33 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has quit
          [Remote host closed the connection]
20:45 -!- jaekwon_ [~omni@75-101-96-71.dsl.static.fusionbroadband.com] has
          joined #scuttlebutt
21:06 -!- tixz [~tixz@82.211.209.116] has joined #scuttlebutt
02:45 < substack> jjjohnny: versions are permanent
02:46 < jjjohnny> but substack that one has fast flashing lights and no warning
02:46 < jjjohnny> our users will be baffled
02:47 -!- rockbot__ [~rockbot__@c-98-207-60-247.hsd1.ca.comcast.net] has joined
          #stackvm
02:47 < substack> jjjohnny: it's not possible to go back and change versions
02:48 < jjjohnny> nyuk nyuk nyuk
02:49 -!- Mso150_z [~ctlM@80.83.238.73] has quit [Ping timeout: 250 seconds]
02:51 -!- phated [~phated@ip72-208-140-83.ph.ph.cox.net] has quit [Ping
          timeout: 265 seconds]
02:51 -!- rockbot__ [~rockbot__@c-98-207-60-247.hsd1.ca.comcast.net] has quit
          [Ping timeout: 255 seconds]
02:54 -!- anvaka [~anvaka@2601:8:ac80:3f9:d4ce:2a55:8f0e:820e] has joined
          #stackvm
02:54 < substack> https://github.com/substack/hyperboot-example-app
02:55 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
02:55 -!- Mso150 [~ctlM@80.83.239.100] has joined #stackvm
02:59 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 258 seconds]
03:04 -!- tixz [~tixz@2001:878:200:1053:64b3:a597:8e78:bdf] has joined #stackvm
03:07 < jjjohnny> MODULARITY SAYS THE CORRECT PROGRAM FOR THIS PROBLEM IS A
                  WRITE ONLY DATABASE
03:07 < LOUDBOT> ORALLY PERHAPS, OR WITH SOME SANDPAPER AND A BOTTLE OF VODKA
03:07 -!- tixz [~tixz@2001:878:200:1053:64b3:a597:8e78:bdf] has quit [Remote
          host closed the connection]
03:07 -!- rannmann [~rez@pdpc/supporter/student/rannmann] has quit [Ping
          timeout: 272 seconds]
03:08 < substack> jjjohnny: well it's just like how npm works
03:08 < jjjohnny> YES TAKEN ONE EVERY 20 NANOSECONDS
03:08 < LOUDBOT> I WILL LEVERAGE MY RIGHTEOUS FURY INTO QUALITY HACKING TIME
03:08 < substack> you can only publish new versions
03:08 < jjjohnny> i was making a joke, substack, making a jokse LIKE A BOSS
03:09 < substack> ah right
03:09 < jjjohnny> the write only database thing is no joke tho, that is pure
                  brilliance
03:10 < terinjokes> jjjohnny: your unix computer comes with one
03:11 < terinjokes> echo 'path!to!the!correct!subtree!key|value' > /dev/null
03:11 < jjjohnny> did somebody say jokes?
03:11 < jjjohnny> haha
03:11 < terinjokes> pretty sure you could get that working with levelup pretty
                    quickly
03:11 < jjjohnny> i was gonna say delete/recycle bin but i knew it wasnt unix
                  enuf
03:12 < substack> write only databases are the only kind of database that won't
                  delete your data
03:13 -!- pfraze [~pfraze@2605:6000:e900:d200:8b7:8612:2a51:502a] has quit
          [Ping timeout: 265 seconds]
03:13 < jjjohnny> substack: but u cant read it so how do you know?
03:13 -!- pfraze [~pfraze@2605:6000:e900:d200:8b7:8612:2a51:502a] has joined
          #stackvm
03:13 < jjjohnny> this is a CS paradox, i found one
03:14 < substack> reading is just an optional feature you can get
03:14 < substack> you can purchase it from a trusted purveyor of fine databases
                  as an after market add-on
03:14 < jjjohnny> free storage get yours
03:17 < substack> the internet is already a write-only database
03:17 < substack> everything you write gets stored in data centers in maryland
                  or utah
03:18 < substack> you just can't get it back out again
03:20 -!- gorhgorh [~gorhgorh@175.229.207.77.rev.sfr.net] has joined #stackvm
03:22 < jjjohnny> jones big ass storage
                  http://www.youtube.com/watch?v=N0gb9v4LI4o
03:26 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has joined #stackvm
03:29 < owen1> substack: i like the idea of
               https://github.com/substack/html-inline  is it being used
               somewhere? is that your version of 'components'?
03:29 -!- djcoin [~djcoin@128-79-237-66.hfc.dyn.abo.bbox.fr] has joined #stackvm
03:30 < jjjohnny> owen1: its 4 making a single file
03:30 < owen1> yeah
03:31 < substack> owen1: I'm just using it for hyperboot
03:31 -!- therealkoopa [~therealko@pool-108-52-202-109.phlapa.fios.verizon.net]
          has quit [Ping timeout: 265 seconds]
03:31 < substack> so that I can just ship around a single html file
03:31 -!- ceejbot [~ceejbot@172-5-154-148.lightspeed.sntcca.sbcglobal.net] has
          joined #stackvm
03:31 < substack> instead of shipping around an archive of files
03:32 -!- stagas [~stagas@athedsl-4412811.home.otenet.gr] has joined #stackvm
03:32 < jjjohnny> substack: does it do css imports?
03:32 < owen1> ok. is hyperboot suppose to be a generic scaffolding for
               offline-first app?
03:33 < owen1> a wrapper on top of the horrific Application Cache?
03:34 < jjjohnny> substack: jk i dont care about css imports
03:35 < owen1> i heard horror stories from App cache, and service workers
03:37 < jjjohnny> service workers is kinda crazy, its like app cache / offline
                  life preserver for the old AJAX websites
03:37 -!- Mso150_x [~ctlM@217.118.64.38] has joined #stackvm
03:37 < jjjohnny> might work out ok since its gonna be a DOM method tho, so
                  thats cool
03:38 < jjjohnny> livecad.wtf
03:38 < jjjohnny> http://livecad.wtf
03:39 < substack> owen1: yes, it's all just wrappers on top of applicationCache
                  but also does the server-side delivery since that's hard to
                  do precisely correct
03:39 -!- _contrahax is now known as contrahax
03:40 -!- Mso150 [~ctlM@80.83.239.100] has quit [Ping timeout: 265 seconds]
03:40 < owen1> substack: so the motivation to build it is to create something
               easier to work with when u want some offline capabilities?
03:45 < substack> owen1: it's more that applicationCache is a means to the
                  objectives listed on hyperboot.org
03:46 < substack> which is primarily about removing the attack vector with
                  browser crypto where the server can decide to send a
                  different payload whenever it wants
03:46 < substack> that everything works offline is a happy bonus
03:49 -!- contrahax is now known as _contrahax
03:51 < jjjohnny> RIP AJAX
03:51 < LOUDBOT> OH HAI, CPAN THIRD OV YUR TEST REPORTS BELONG TO ME.
03:51 < jjjohnny> hyperboot is the NPM for apps
03:51 < jjjohnny> web apps
03:52 < jjjohnny> apps that connect to each other
03:52 < jjjohnny> via a network of tubes
03:52 < jjjohnny> these tubes are filled with microtubes
03:53 < jjjohnny> microtubes look like hairs
03:53 < jjjohnny> the internet if tubes looks like up your nose
03:54 < jjjohnny> the microtubes run perpendicular to the macro tubes
03:54 < jjjohnny> thus the view down an inter tube looks like spoke wheel
03:55 < jjjohnny> a spoked wheel animated by the ghost of salvador dali
03:55 < jjjohnny> that is the fundamentally the view of the "internet of webs",
                  or the "web all the things" meme
 Unofficial browserling/testling mad science channel. For official help /join #b
03:56 < jjjohnny> i am a spider that is not a spider but all spiders, and you
                  are swine
03:57 < jjjohnny> that is why I can tell you these things, pig
03:57 < jjjohnny> and why you better believe them, hog, before your time starts
                  cooking
03:58 < jjjohnny> here let me spin your a story
03:59 < jjjohnny> its called the story of the facts i delivered to your moments
                  ago
03:59 < jjjohnny> and i shall spin it into a single image
03:59 < jjjohnny> i will summon the web formula
03:59 < jjjohnny> looks at my web
04:00 < jjjohnny> thats is what it looks like down an internet tubes the long
                  way
04:00 < jjjohnny> this is a two dimension image, you see, this web is an
                  isomorph
04:01 < jjjohnny> well, a 2d image broken into fractal animation by the wind of
                  the ghost of dali
04:01 < jjjohnny> do you smell thunder, swine?
04:03  * jjjohnny calls this story charletans' webs'
04:04 < jjjohnny> which can be logically translated to the contents of those
                  webs
 [04:05] [jjjohnny(+i)] [3:freenode/#stackvm(+cnt)] [Act: 4,5]
[#stackvm]
