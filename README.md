Last login: Thu Nov 29 21:35:30 on ttys001
Cadmans-MacBook-Pro:~ cadmanchui$ cd eon
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
ssh: connect to host 192.168.1.210 port 8022: Host is down
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
ssh: connect to host 192.168.1.210 port 8022: Host is down
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
root@localhost:/system/comma/home$ cd /data/openpilot
root@localhost:/data/openpilot$ git pull
Already up to date.
root@localhost:/data/openpilot$ packet_write_poll: Connection to 192.168.1.210 port 8022: Host is down
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
ssh: connect to host 192.168.1.210 port 8022: Host is down
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
ssh: connect to host 192.168.1.210 port 8022: Host is down
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
^C
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
ssh: connect to host 192.168.1.210 port 8022: Host is down
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
^C
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
root@localhost:/system/comma/home$ cd /data/openpilot
root@localhost:/data/openpilot$ git pull
remote: Enumerating objects: 11, done.
remote: Counting objects: 100% (11/11), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 6 (delta 5), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
From https://github.com/kegman/openpilot
   3d20142..56df784  kegman-test -> origin/kegman-test
Updating 3d20142..56df784
Fast-forward
 selfdrive/controls/lib/planner.py | 2 --
 1 file changed, 2 deletions(-)
root@localhost:/data/openpilot$ packet_write_wait: Connection to 192.168.1.210 port 8022: Broken pipe
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
root@localhost:/system/comma/home$ cd /data/openpilot
root@localhost:/data/openpilot$ git pull
remote: Enumerating objects: 11, done.
remote: Counting objects: 100% (11/11), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 6 (delta 5), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
From https://github.com/kegman/openpilot
   56df784..a8a3ee1  kegman-test -> origin/kegman-test
Updating 56df784..a8a3ee1
Fast-forward
 selfdrive/controls/lib/planner.py | 45 +++++++++++++++++++--------------------
 1 file changed, 22 insertions(+), 23 deletions(-)
root@localhost:/data/openpilot$ packet_write_wait: Connection to 192.168.1.210 port 8022: Broken pipe
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
root@localhost:/system/comma/home$ cd /data/openpilot
root@localhost:/data/openpilot$ git pull
Already up to date.
root@localhost:/data/openpilot$ packet_write_wait: Connection to 192.168.1.210 port 8022: Broken pipe
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
root@localhost:/system/comma/home$ cd /data/op*
bash: cd: too many arguments
root@localhost:/system/comma/home$ cd /data/openpilot
root@localhost:/data/openpilot$ git stash
Saved working directory and index state WIP on kegman-test: a8a3ee1 Flatten out elif ladder for autodistance
root@localhost:/data/openpilot$ git pull
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
From https://github.com/kegman/openpilot
   a8a3ee1..7795293  kegman-test -> origin/kegman-test
Updating a8a3ee1..7795293
Fast-forward
 selfdrive/controls/lib/planner.py | 22 +++++++++-------------
 1 file changed, 9 insertions(+), 13 deletions(-)
root@localhost:/data/openpilot$ git status
On branch kegman-test
Your branch is up to date with 'origin/kegman-test'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	selfdrive/log.txt

nothing added to commit but untracked files present (use "git add" to track)
root@localhost:/data/openpilot$ cd ..
root@localhost:/data$ cd ..
root@localhost:/$ cd data
root@localhost:/data$ cd openpilot/selfdrive
root@localhost:/data/openpilot/selfdrive$ rm log.txt
root@localhost:/data/openpilot/selfdrive$ git status -v
On branch kegman-test
Your branch is up to date with 'origin/kegman-test'.

nothing to commit, working tree clean
root@localhost:/data/openpilot/selfdrive$ git pull
Already up to date.
root@localhost:/data/openpilot/selfdrive$ packet_write_wait: Connection to 192.168.1.210 port 8022: Broken pipe
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
root@localhost:/system/comma/home$ cd /data/openpilot
root@localhost:/data/openpilot$ git pull
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
From https://github.com/kegman/openpilot
   7795293..71ead61  kegman-test -> origin/kegman-test
Updating 7795293..71ead61
Fast-forward
 selfdrive/controls/lib/planner.py | 20 +++-----------------
 1 file changed, 3 insertions(+), 17 deletions(-)
root@localhost:/data/openpilot$ packet_write_wait: Connection to 192.168.1.210 port 8022: Broken pipe
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
root@localhost:/system/comma/home$ cd /data/openpilot
root@localhost:/data/openpilot$ grep -r "every minute" .
root@localhost:/data/openpilot$ grep -r "degrees" .
./cereal/log.capnp:  # Represents latitude in degrees.
./cereal/log.capnp:  # Represents longitude in degrees.
./cereal/log.capnp:  # Represents heading in degrees.
./cereal/log.capnp:  # Represents bearing accuracy in degrees. (presumably 1 sigma?)
./cereal/log.capnp:  angleSteers @13 :Float32;     # Steering angle in degrees.
./opendbc/ford_cgea1_2_bodycan_2011.dbc: SG_ AmbTempImpr : 7|10@0+ (0.25,-128.0) [0|0] "degreesC" XXX
./opendbc/ford_cgea1_2_bodycan_2011.dbc: SG_ InCarTemp : 39|8@0+ (0.5,-57.0) [0|0] "degreesC" XXX
./opendbc/ford_cgea1_2_bodycan_2011.dbc: SG_ VehHead_W_Actl : 23|16@0+ (0.01,-327.68) [0|0] "degrees/second" XXX
./opendbc/ford_cgea1_2_bodycan_2011.dbc: SG_ VehHead_An_Est : 7|16@0+ (0.01,0) [0|0] "degrees" XXX
./opendbc/ford_cgea1_2_ptcan_2011.dbc: SG_ AmbTempImpr : 47|10@0+ (0.25,-128.0) [0|0] "degreesC" XXX
./opendbc/mercedes_benz_e350_2010.dbc: SG_ STEER_ANGLE : 3|12@0- (-0.5,0) [-500|500] "degrees" XXX
./opendbc/toyota_iQ_2009_can.dbc:CM_ SG_ 37 STEER_ANGLE "can convert to degrees (imprecise) or percentage of max amplitude";
./panda/board/safety/safety_toyota_ipas.h:const float CAN_TO_DEG = 2. / 3.;      // convert angles from CAN unit to degrees
./panda/examples/query_vin_and_stats.py:    temp = struct.unpack(">B", get_current_data_for_pid(5)[2:])[0] - 40               # degrees C
./phonelibs/nanovg/nanovg.h:// Converts degrees to radians and vice versa.
./pyextra/utm/conversion.py:    return (math.degrees(latitude),
./pyextra/utm/conversion.py:            math.degrees(longitude) + zone_number_to_central_longitude(zone_number))
./selfdrive/common/framebuffer.cc:  //int orientation = 3; // rotate framebuffer 270 degrees
./selfdrive/common/framebuffer.cc:  int orientation = 1; // rotate framebuffer 90 degrees
./selfdrive/controls/lib/driver_monitor.py:    #print "%02.4f" % np.degrees(pose.pitch), "%02.4f" % np.degrees(pitch_error), "%03.4f" % np.degrees(pose.pitch_offset), metric
./selfdrive/controls/lib/latcontrol.py:      self.angle_steers_des_mpc = float(math.degrees(delta_desired * CP.steerRatio) + angle_offset)
./selfdrive/controls/lib/latcontrol_helpers.py:  steer_des = math.degrees(VM.get_steer_from_curvature(curvature, v_ego)) + angle_offset
Binary file ./selfdrive/controls/lib/latcontrol_helpers.pyc matches
Binary file ./selfdrive/controls/lib/latcontrol.pyc matches
./selfdrive/locationd/ubloxd.py:  gps_fix = {'bearing': msg_data['headMot']*1e-05,  # heading of motion in degrees
./selfdrive/locationd/ubloxd.py:             'latitude': msg_data['lat']*1e-07,  # latitude in degrees
./selfdrive/locationd/ubloxd.py:             'longitude': msg_data['lon']*1e-07,  # longitude in degrees
./selfdrive/locationd/ubloxd.py:             'bearingAccuracy': msg_data['headAcc']*1e-05,  # heading accuracy in degrees
./selfdrive/test/plant/plant_ui.py:    display.blit(pygame.transform.rotate(car, 90-math.degrees(heading)), (carx*METER, cary*METER))
./selfdrive/test/plant/plant_ui.py:    display.blit(pygame.transform.rotate(leadcar, 90-math.degrees(heading)), (lx*METER, ly*METER))
root@localhost:/data/openpilot$ git pull
Already up to date.
root@localhost:/data/openpilot$ packet_write_wait: Connection to 192.168.1.210 port 8022: Broken pipe
Cadmans-MacBook-Pro:eon cadmanchui$ tmux a
-bash: tmux: command not found
Cadmans-MacBook-Pro:eon cadmanchui$ tmux a
-bash: tmux: command not found
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
root@localhost:/system/comma/home$ tmux a
[detached (from session comma)]
root@localhost:/system/comma/home$ cd /data/openpilot
root@localhost:/data/openpilot$ exit
logout
Connection to 192.168.1.210 closed.
Cadmans-MacBook-Pro:eon cadmanchui$ cd /openpilot
-bash: cd: /openpilot: No such file or directory
Cadmans-MacBook-Pro:eon cadmanchui$ cd ..
Cadmans-MacBook-Pro:~ cadmanchui$ cd openpilot
Cadmans-MacBook-Pro:openpilot cadmanchui$ ls
CONTRIBUTING.md			installer
Dockerfile.openpilot		launch_chffrplus.sh
LICENSE				launch_openpilot.sh
Makefile			opendbc
README.md			panda
README_chffrplus.md		phonelibs
RELEASES.md			pyextra
SAFETY.md			requirements_openpilot.txt
apk				run_docker_tests.sh
cereal				selfdrive
common
Cadmans-MacBook-Pro:openpilot cadmanchui$ git branch -a
  kegman-devel
* kegman-test
  remotes/gernby/Camera_Devel
  remotes/gernby/Feed-Forward-Scratch-Pad
  remotes/gernby/Feed-Forward-Zero-Crossing
  remotes/gernby/Feed-Forward_Steer_Offset
  remotes/gernby/OP_5_6
  remotes/gernby/devel
  remotes/gernby/hotfix-5.5.5-visiond
  remotes/gernby/lane-width-filter-fix
  remotes/gernby/release2
  remotes/gernby/steering_devel
  remotes/gernby/temp_branch
  remotes/gernby/toyota-radar-filtering
  remotes/origin/HEAD -> origin/kegman-devel
  remotes/origin/comma-devel
  remotes/origin/kegman-devel
  remotes/origin/kegman-devel-defaultPID
  remotes/origin/kegman-test
Cadmans-MacBook-Pro:openpilot cadmanchui$ git fetch
remote: Enumerating objects: 62, done.
remote: Counting objects: 100% (62/62), done.
remote: Compressing objects: 100% (12/12), done.
remote: Total 72 (delta 55), reused 50 (delta 50), pack-reused 10
Unpacking objects: 100% (72/72), done.
From https://github.com/kegman/openpilot
   f5732df..71ead61  kegman-test          -> origin/kegman-test
 * [new branch]      kegman-china-odyssey -> origin/kegman-china-odyssey
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout kegman-china-odyssey
Branch 'kegman-china-odyssey' set up to track remote branch 'kegman-china-odyssey' from 'origin'.
Switched to a new branch 'kegman-china-odyssey'
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout -b energee-odyssey-china kegman-china-odyssey
Switched to a new branch 'energee-odyssey-china'
Cadmans-MacBook-Pro:openpilot cadmanchui$ git pull https://github.com/energee/openpilot.git odyssey-china
remote: Enumerating objects: 101, done.
remote: Counting objects: 100% (101/101), done.
remote: Total 173 (delta 100), reused 100 (delta 100), pack-reused 72
Receiving objects: 100% (173/173), 35.72 KiB | 1.23 MiB/s, done.
Resolving deltas: 100% (134/134), completed with 22 local objects.
From https://github.com/energee/openpilot
 * branch            odyssey-china -> FETCH_HEAD
warning: Cannot merge binary files: apk/ai.comma.plus.offroad.apk (HEAD vs. f01c7acd65eeb165dd9870a180c1552077bc0ea4)
Auto-merging selfdrive/controls/lib/alertmanager.py
CONFLICT (content): Merge conflict in selfdrive/controls/lib/alertmanager.py
Auto-merging selfdrive/controls/controlsd.py
CONFLICT (content): Merge conflict in selfdrive/controls/controlsd.py
Auto-merging selfdrive/car/hyundai/values.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/values.py
Auto-merging selfdrive/car/hyundai/interface.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/interface.py
Auto-merging selfdrive/car/hyundai/carstate.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/carstate.py
Auto-merging selfdrive/car/honda/values.py
CONFLICT (content): Merge conflict in selfdrive/car/honda/values.py
Auto-merging selfdrive/car/honda/interface.py
Auto-merging selfdrive/car/honda/hondacan.py
CONFLICT (content): Merge conflict in selfdrive/car/honda/hondacan.py
Auto-merging selfdrive/car/honda/carstate.py
Auto-merging selfdrive/car/honda/carcontroller.py
Auto-merging selfdrive/car/gm/interface.py
CONFLICT (content): Merge conflict in selfdrive/car/gm/interface.py
Auto-merging selfdrive/car/gm/carcontroller.py
CONFLICT (content): Merge conflict in selfdrive/car/gm/carcontroller.py
Auto-merging panda/VERSION
CONFLICT (content): Merge conflict in panda/VERSION
Auto-merging opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc
CONFLICT (add/add): Merge conflict in opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc
Auto-merging cereal/car.capnp
CONFLICT (content): Merge conflict in cereal/car.capnp
Auto-merging apk/ai.comma.plus.offroad.apk
CONFLICT (content): Merge conflict in apk/ai.comma.plus.offroad.apk
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/controls/lib/alertmanager.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git branch
* energee-odyssey-china
  kegman-china-odyssey
  kegman-devel
  kegman-test
Cadmans-MacBook-Pro:openpilot cadmanchui$ git cherry-pick 405140c5563d5e9759c6b740f0ac3a0cdb775634
error: Cherry-picking is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: cherry-pick failed
Cadmans-MacBook-Pro:openpilot cadmanchui$ git stash
README.md: needs merge
apk/ai.comma.plus.offroad.apk: needs merge
cereal/car.capnp: needs merge
opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc: needs merge
panda/VERSION: needs merge
selfdrive/car/gm/carcontroller.py: needs merge
selfdrive/car/gm/interface.py: needs merge
selfdrive/car/honda/hondacan.py: needs merge
selfdrive/car/honda/values.py: needs merge
selfdrive/car/hyundai/carstate.py: needs merge
selfdrive/car/hyundai/interface.py: needs merge
selfdrive/car/hyundai/values.py: needs merge
selfdrive/controls/controlsd.py: needs merge
selfdrive/controls/lib/alertmanager.py: needs merge
README.md: needs merge
apk/ai.comma.plus.offroad.apk: needs merge
cereal/car.capnp: needs merge
opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc: needs merge
panda/VERSION: needs merge
selfdrive/car/gm/carcontroller.py: needs merge
selfdrive/car/gm/interface.py: needs merge
selfdrive/car/honda/hondacan.py: needs merge
selfdrive/car/honda/values.py: needs merge
selfdrive/car/hyundai/carstate.py: needs merge
selfdrive/car/hyundai/interface.py: needs merge
selfdrive/car/hyundai/values.py: needs merge
selfdrive/controls/controlsd.py: needs merge
selfdrive/controls/lib/alertmanager.py: needs merge
README.md: unmerged (dec4d00ae12af0fbd253b08f43d5d0b6a14af32d)
README.md: unmerged (6393503ed7ed75b2c416e88dea069dea299ef5bc)
README.md: unmerged (ae6b0ed66f6ca8c3013a6216108c8a1e9175573a)
apk/ai.comma.plus.offroad.apk: unmerged (489bdd7e73d6c96c844b04826e0fc66bbcb15135)
apk/ai.comma.plus.offroad.apk: unmerged (a9e5738a40cd3c8b309559139b937461d3877e63)
apk/ai.comma.plus.offroad.apk: unmerged (7453cd10a47e87b8a647f6c0540d84bbf9696ebf)
cereal/car.capnp: unmerged (c14ed5b99781b37500b7b220671b9edfd649f595)
cereal/car.capnp: unmerged (58d3fbdc0212a564d5ede9df29d2e0481e1d9287)
cereal/car.capnp: unmerged (ff1297f1ef8095943e027966b1dc5292f418691d)
opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc: unmerged (ad66716f35cc01952fb3c9657c9fd75f9e9f52b2)
...
fatal: git-write-tree: error building trees
Cannot save the current index state
Cadmans-MacBook-Pro:openpilot cadmanchui$ git pull
error: Pulling is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
Cadmans-MacBook-Pro:openpilot cadmanchui$ ls
CONTRIBUTING.md			installer
Dockerfile.openpilot		launch_chffrplus.sh
LICENSE				launch_openpilot.sh
Makefile			opendbc
README.md			panda
README_chffrplus.md		phonelibs
RELEASES.md			pyextra
SAFETY.md			requirements_openpilot.txt
apk				run_docker_tests.sh
cereal				selfdrive
common
Cadmans-MacBook-Pro:openpilot cadmanchui$ git pull
error: Pulling is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
Cadmans-MacBook-Pro:openpilot cadmanchui$ ls
CONTRIBUTING.md			installer
Dockerfile.openpilot		launch_chffrplus.sh
LICENSE				launch_openpilot.sh
Makefile			opendbc
README.md			panda
README_chffrplus.md		phonelibs
RELEASES.md			pyextra
SAFETY.md			requirements_openpilot.txt
apk				run_docker_tests.sh
cereal				selfdrive
common
Cadmans-MacBook-Pro:openpilot cadmanchui$ git branch
* energee-odyssey-china
  kegman-china-odyssey
  kegman-devel
  kegman-test
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout kegman-china-odyssey
README.md: needs merge
apk/ai.comma.plus.offroad.apk: needs merge
cereal/car.capnp: needs merge
opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc: needs merge
panda/VERSION: needs merge
selfdrive/car/gm/carcontroller.py: needs merge
selfdrive/car/gm/interface.py: needs merge
selfdrive/car/honda/hondacan.py: needs merge
selfdrive/car/honda/values.py: needs merge
selfdrive/car/hyundai/carstate.py: needs merge
selfdrive/car/hyundai/interface.py: needs merge
selfdrive/car/hyundai/values.py: needs merge
selfdrive/controls/controlsd.py: needs merge
selfdrive/controls/lib/alertmanager.py: needs merge
error: you need to resolve your current index first
Cadmans-MacBook-Pro:openpilot cadmanchui$ cd ..
Cadmans-MacBook-Pro:~ cadmanchui$ rm -rf ./openpilot
Cadmans-MacBook-Pro:~ cadmanchui$ git clone https://github.com/kegman/openpilot
Cloning into 'openpilot'...
remote: Enumerating objects: 13, done.
remote: Counting objects: 100% (13/13), done.
remote: Compressing objects: 100% (13/13), done.
remote: Total 5782 (delta 5), reused 0 (delta 0), pack-reused 5769
Receiving objects: 100% (5782/5782), 348.78 MiB | 3.53 MiB/s, done.
Resolving deltas: 100% (3396/3396), done.
Cadmans-MacBook-Pro:~ cadmanchui$ cd openpilot
Cadmans-MacBook-Pro:openpilot cadmanchui$ grep -r "china" .
Binary file ./.git/index matches
./.git/packed-refs:71ead61b7b10c9419b1b31a0e8ebf4aabd4c43f6 refs/remotes/origin/kegman-china-odyssey
Cadmans-MacBook-Pro:openpilot cadmanchui$ cd ..
Cadmans-MacBook-Pro:~ cadmanchui$ cd openpilot
Cadmans-MacBook-Pro:openpilot cadmanchui$ ls
CONTRIBUTING.md			installer
Dockerfile.openpilot		launch_chffrplus.sh
LICENSE				launch_openpilot.sh
Makefile			opendbc
README.md			panda
README_chffrplus.md		phonelibs
RELEASES.md			pyextra
SAFETY.md			requirements_openpilot.txt
apk				run_docker_tests.sh
cereal				selfdrive
common
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout kegman-china-odyssey
Branch 'kegman-china-odyssey' set up to track remote branch 'kegman-china-odyssey' from 'origin'.
Switched to a new branch 'kegman-china-odyssey'
Cadmans-MacBook-Pro:openpilot cadmanchui$ git cherrypick 405140c5563d5e9759c6b740f0ac3a0cdb775634
git: 'cherrypick' is not a git command. See 'git --help'.

The most similar command is
	cherry-pick
Cadmans-MacBook-Pro:openpilot cadmanchui$ git cherry-pick 405140c5563d5e9759c6b740f0ac3a0cdb775634
fatal: bad object 405140c5563d5e9759c6b740f0ac3a0cdb775634
Cadmans-MacBook-Pro:openpilot cadmanchui$ git remote -v
origin	https://github.com/kegman/openpilot (fetch)
origin	https://github.com/kegman/openpilot (push)
Cadmans-MacBook-Pro:openpilot cadmanchui$ git remote add upstream https://github.com/commaai/openpilot
Cadmans-MacBook-Pro:openpilot cadmanchui$ git cherry-pick 405140c5563d5e9759c6b740f0ac3a0cdb775634
fatal: bad object 405140c5563d5e9759c6b740f0ac3a0cdb775634
Cadmans-MacBook-Pro:openpilot cadmanchui$ git remote -v
origin	https://github.com/kegman/openpilot (fetch)
origin	https://github.com/kegman/openpilot (push)
upstream	https://github.com/commaai/openpilot (fetch)
upstream	https://github.com/commaai/openpilot (push)
Cadmans-MacBook-Pro:openpilot cadmanchui$ git cherry-pick upstream/405140c5563d5e9759c6b740f0ac3a0cdb775634
fatal: bad revision 'upstream/405140c5563d5e9759c6b740f0ac3a0cdb775634'
Cadmans-MacBook-Pro:openpilot cadmanchui$ git cherry-pick 
usage: git cherry-pick [<options>] <commit-ish>...
   or: git cherry-pick <subcommand>

    --quit                end revert or cherry-pick sequence
    --continue            resume revert or cherry-pick sequence
    --abort               cancel revert or cherry-pick sequence
    -n, --no-commit       don't automatically commit
    -e, --edit            edit the commit message
    -s, --signoff         add Signed-off-by:
    -m, --mainline <parent-number>
                          select mainline parent
    --rerere-autoupdate   update the index with reused conflict resolution if possible
    --strategy <strategy>
                          merge strategy
    -X, --strategy-option <option>
                          option for merge strategy
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit
    -x                    append commit name
    --ff                  allow fast-forward
    --allow-empty         preserve initially empty commits
    --allow-empty-message
                          allow commits with empty messages
    --keep-redundant-commits
                          keep redundant, empty commits

Cadmans-MacBook-Pro:openpilot cadmanchui$ git cherry-pick 405140c5563d5e9759c6b740f0ac3a0cdb775634
fatal: bad object 405140c5563d5e9759c6b740f0ac3a0cdb775634
Cadmans-MacBook-Pro:openpilot cadmanchui$ git remote add upstream https://github.com/energee/openpilot
fatal: remote upstream already exists.
Cadmans-MacBook-Pro:openpilot cadmanchui$ git remote add energee https://github.com/energee/openpilot
Cadmans-MacBook-Pro:openpilot cadmanchui$ git cherry-pick 405140c5563d5e9759c6b740f0ac3a0cdb775634
fatal: bad object 405140c5563d5e9759c6b740f0ac3a0cdb775634
Cadmans-MacBook-Pro:openpilot cadmanchui$ git remote -v
energee	https://github.com/energee/openpilot (fetch)
energee	https://github.com/energee/openpilot (push)
origin	https://github.com/kegman/openpilot (fetch)
origin	https://github.com/kegman/openpilot (push)
upstream	https://github.com/commaai/openpilot (fetch)
upstream	https://github.com/commaai/openpilot (push)
Cadmans-MacBook-Pro:openpilot cadmanchui$ grep -r "learn_angle_offset" .
./selfdrive/controls/lib/drive_helpers.py:def learn_angle_offset(lateral_control, v_ego, angle_offset, c_poly, c_prob, angle_steers, steer_override):
./selfdrive/controls/controlsd.py:from selfdrive.controls.lib.drive_helpers import learn_angle_offset, \
./selfdrive/controls/controlsd.py:    angle_offset = learn_angle_offset(active, CS.vEgo, angle_offset,
Cadmans-MacBook-Pro:openpilot cadmanchui$ cd ..
Cadmans-MacBook-Pro:~ cadmanchui$ rm -rf ./openpilot
Cadmans-MacBook-Pro:~ cadmanchui$ git clone https://github.com/kegman/openpilot
Cloning into 'openpilot'...
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 5788 (delta 0), reused 0 (delta 0), pack-reused 5781
Receiving objects: 100% (5788/5788), 348.78 MiB | 3.51 MiB/s, done.
Resolving deltas: 100% (3402/3402), done.
Cadmans-MacBook-Pro:~ cadmanchui$ cd openpilot
Cadmans-MacBook-Pro:openpilot cadmanchui$ git remote -v
origin	https://github.com/kegman/openpilot (fetch)
origin	https://github.com/kegman/openpilot (push)
Cadmans-MacBook-Pro:openpilot cadmanchui$ git remote add upstream https://github.com/commaai/openpilot
Cadmans-MacBook-Pro:openpilot cadmanchui$ git fetch upstream
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Total 36 (delta 6), reused 6 (delta 6), pack-reused 30
Unpacking objects: 100% (36/36), done.
From https://github.com/commaai/openpilot
 * [new branch]      devel      -> upstream/devel
 * [new branch]      release2   -> upstream/release2
Cadmans-MacBook-Pro:openpilot cadmanchui$ git status -v
On branch kegman-devel
Your branch is up to date with 'origin/kegman-devel'.

nothing to commit, working tree clean
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout kegman-devel
Already on 'kegman-devel'
Your branch is up to date with 'origin/kegman-devel'.
Cadmans-MacBook-Pro:openpilot cadmanchui$ git rebase -i upstream/devel
Successfully rebased and updated refs/heads/kegman-devel.
Cadmans-MacBook-Pro:openpilot cadmanchui$ git push -f origin
Counting objects: 137, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (91/91), done.
Writing objects: 100% (137/137), 26.74 KiB | 5.35 MiB/s, done.
Total 137 (delta 116), reused 49 (delta 46)
remote: Resolving deltas: 100% (116/116), completed with 27 local objects.
To https://github.com/kegman/openpilot
 + 812823b...2bbbcc5 kegman-devel -> kegman-devel (forced update)
Cadmans-MacBook-Pro:openpilot cadmanchui$ cd ..
Cadmans-MacBook-Pro:~ cadmanchui$ cd eon
Cadmans-MacBook-Pro:eon cadmanchui$ ssh root@192.168.1.210 -p 8022 -i eonkey.pem
root@localhost:/system/comma/home$ cd /data/openpilot
root@localhost:/data/openpilot$ git checkout kegman-devel
Switched to branch 'kegman-devel'
Your branch is up to date with 'origin/kegman-devel'.
root@localhost:/data/openpilot$ git pull
remote: Enumerating objects: 76, done.
remote: Counting objects: 100% (76/76), done.
remote: Compressing objects: 100% (25/25), done.
remote: Total 77 (delta 55), reused 66 (delta 51), pack-reused 1
Unpacking objects: 100% (77/77), done.
From https://github.com/kegman/openpilot
 + 83a9737...2bbbcc5 kegman-devel            -> origin/kegman-devel  (forced update)
 + f0bbfa4...9fb6993 kegman-devel-defaultPID -> origin/kegman-devel-defaultPID  (forced update)
Auto-merging selfdrive/controls/lib/planner.py
CONFLICT (content): Merge conflict in selfdrive/controls/lib/planner.py
Auto-merging selfdrive/car/honda/interface.py
Automatic merge failed; fix conflicts and then commit the result.
root@localhost:/data/openpilot$ cd ..
root@localhost:/data$ ls
adb	     bugreports    fpc	       nfc		 shared
app	     connectivity  fpc_images  oemnvitems	 ss
app-asec     core	   hostapd     openpilot	 ssh
app-lib      dalvik-cache  local       openpilot.backup  system
app-private  data	   lost+found  params		 time
audio	     dpm	   media       property		 tombstones
backup	     drm	   mediadrm    resource-cache	 user
bootchart    fota	   misc        security		 usf
root@localhost:/data$ rm -rf ./openpilot
root@localhost:/data$ git clone https://github.com/kegman/openpilot
Cloning into 'openpilot'...
remote: Enumerating objects: 71, done.
remote: Counting objects: 100% (71/71), done.
remote: Compressing objects: 100% (38/38), done.
remote: Total 5853 (delta 45), reused 48 (delta 33), pack-reused 5782
Receiving objects: 100% (5853/5853), 348.79 MiB | 3.44 MiB/s, done.
Resolving deltas: 100% (3448/3448), done.
root@localhost:/data$ packet_write_wait: Connection to 192.168.1.210 port 8022: Broken pipe
Cadmans-MacBook-Pro:eon cadmanchui$ cd ~
Cadmans-MacBook-Pro:~ cadmanchui$ cd openpilot
Cadmans-MacBook-Pro:openpilot cadmanchui$ git branch
* kegman-devel
Cadmans-MacBook-Pro:openpilot cadmanchui$ grep -r "learn_angle" .
./selfdrive/controls/lib/drive_helpers.py:def learn_angle_offset(lateral_control, v_ego, angle_offset, c_poly, c_prob, angle_steers, steer_override):
./selfdrive/controls/controlsd.py:from selfdrive.controls.lib.drive_helpers import learn_angle_offset, \
./selfdrive/controls/controlsd.py:    angle_offset = learn_angle_offset(active, CS.vEgo, angle_offset,
Cadmans-MacBook-Pro:openpilot cadmanchui$ cd ..
Cadmans-MacBook-Pro:~ cadmanchui$ rm -rf ./openpilot
Cadmans-MacBook-Pro:~ cadmanchui$ git clone https://github.com/kegman/openpilot
Cloning into 'openpilot'...
remote: Enumerating objects: 83, done.
remote: Counting objects: 100% (83/83), done.
remote: Compressing objects: 100% (43/43), done.
remote: Total 5608 (delta 56), reused 55 (delta 40), pack-reused 5525
Receiving objects: 100% (5608/5608), 348.76 MiB | 3.53 MiB/s, done.
Resolving deltas: 100% (3250/3250), done.
Cadmans-MacBook-Pro:~ cadmanchui$ cd openpilot
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout kegman-odyssey-china
Branch 'kegman-odyssey-china' set up to track remote branch 'kegman-odyssey-china' from 'origin'.
Switched to a new branch 'kegman-odyssey-china'
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout -b energee-odyssey-china kegman-odyssey-china
Switched to a new branch 'energee-odyssey-china'
Cadmans-MacBook-Pro:openpilot cadmanchui$ git pull https://github.com/energee/openpilot.git odyssey-china
remote: Enumerating objects: 101, done.
remote: Counting objects: 100% (101/101), done.
remote: Total 173 (delta 101), reused 101 (delta 101), pack-reused 72
Receiving objects: 100% (173/173), 30.78 KiB | 10.26 MiB/s, done.
Resolving deltas: 100% (135/135), completed with 23 local objects.
From https://github.com/energee/openpilot
 * branch            odyssey-china -> FETCH_HEAD
warning: Cannot merge binary files: apk/ai.comma.plus.offroad.apk (HEAD vs. f01c7acd65eeb165dd9870a180c1552077bc0ea4)
Auto-merging selfdrive/controls/lib/alertmanager.py
CONFLICT (content): Merge conflict in selfdrive/controls/lib/alertmanager.py
Auto-merging selfdrive/controls/controlsd.py
CONFLICT (content): Merge conflict in selfdrive/controls/controlsd.py
Auto-merging selfdrive/car/hyundai/values.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/values.py
Auto-merging selfdrive/car/hyundai/interface.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/interface.py
Auto-merging selfdrive/car/hyundai/carstate.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/carstate.py
Auto-merging selfdrive/car/honda/values.py
CONFLICT (content): Merge conflict in selfdrive/car/honda/values.py
Auto-merging selfdrive/car/honda/interface.py
Auto-merging selfdrive/car/honda/hondacan.py
CONFLICT (content): Merge conflict in selfdrive/car/honda/hondacan.py
Auto-merging selfdrive/car/honda/carstate.py
Auto-merging selfdrive/car/honda/carcontroller.py
Auto-merging selfdrive/car/gm/interface.py
CONFLICT (content): Merge conflict in selfdrive/car/gm/interface.py
Auto-merging selfdrive/car/gm/carcontroller.py
CONFLICT (content): Merge conflict in selfdrive/car/gm/carcontroller.py
Auto-merging panda/VERSION
CONFLICT (content): Merge conflict in panda/VERSION
Auto-merging opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc
CONFLICT (add/add): Merge conflict in opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc
Auto-merging cereal/car.capnp
CONFLICT (content): Merge conflict in cereal/car.capnp
Auto-merging apk/ai.comma.plus.offroad.apk
CONFLICT (content): Merge conflict in apk/ai.comma.plus.offroad.apk
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout kegman-odyssey-china
README.md: needs merge
apk/ai.comma.plus.offroad.apk: needs merge
cereal/car.capnp: needs merge
opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc: needs merge
panda/VERSION: needs merge
selfdrive/car/gm/carcontroller.py: needs merge
selfdrive/car/gm/interface.py: needs merge
selfdrive/car/honda/hondacan.py: needs merge
selfdrive/car/honda/values.py: needs merge
selfdrive/car/hyundai/carstate.py: needs merge
selfdrive/car/hyundai/interface.py: needs merge
selfdrive/car/hyundai/values.py: needs merge
selfdrive/controls/controlsd.py: needs merge
selfdrive/controls/lib/alertmanager.py: needs merge
error: you need to resolve your current index first
Cadmans-MacBook-Pro:openpilot cadmanchui$ git branch
* energee-odyssey-china
  kegman-devel
  kegman-odyssey-china
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi README.md
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add README.md
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi apk/ai.comma.plus.offroad.apk
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add apk/ai.comma.plus.offroad.apk
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi cereal/car.capnp
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add cereal/car.capnp
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi panda/VERSION
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi panda/VERSION
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add panda/VERSION
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/gm/carcontroller.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/car/gm/carcontroller.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/gm/interface.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/car/gm/interface.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/honda/hondacan.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/car/honda/hondacan.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/honda/values.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/honda/values.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/car/honda/values.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ cd ..
Cadmans-MacBook-Pro:~ cadmanchui$ rm -rf ./openpilot
Cadmans-MacBook-Pro:~ cadmanchui$ git clone https://github.com/kegman/openpilot
Cloning into 'openpilot'...
remote: Enumerating objects: 83, done.
remote: Counting objects: 100% (83/83), done.
remote: Compressing objects: 100% (43/43), done.
remote: Total 5608 (delta 56), reused 55 (delta 40), pack-reused 5525
Receiving objects: 100% (5608/5608), 348.76 MiB | 3.47 MiB/s, done.
Resolving deltas: 100% (3250/3250), done.
Cadmans-MacBook-Pro:~ cadmanchui$ cd openpilot
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout -b energee-odyssey-china kegman-devel
Switched to a new branch 'energee-odyssey-china'
Cadmans-MacBook-Pro:openpilot cadmanchui$ git pull https://github.com/energee/openpilot.git odyssey-china
remote: Enumerating objects: 101, done.
remote: Counting objects: 100% (101/101), done.
remote: Total 173 (delta 101), reused 101 (delta 101), pack-reused 72
Receiving objects: 100% (173/173), 30.78 KiB | 10.26 MiB/s, done.
Resolving deltas: 100% (135/135), completed with 23 local objects.
From https://github.com/energee/openpilot
 * branch            odyssey-china -> FETCH_HEAD
warning: Cannot merge binary files: apk/ai.comma.plus.offroad.apk (HEAD vs. f01c7acd65eeb165dd9870a180c1552077bc0ea4)
Auto-merging selfdrive/controls/lib/alertmanager.py
CONFLICT (content): Merge conflict in selfdrive/controls/lib/alertmanager.py
Auto-merging selfdrive/controls/controlsd.py
CONFLICT (content): Merge conflict in selfdrive/controls/controlsd.py
Auto-merging selfdrive/car/hyundai/values.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/values.py
Auto-merging selfdrive/car/hyundai/interface.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/interface.py
Auto-merging selfdrive/car/hyundai/carstate.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/carstate.py
Auto-merging selfdrive/car/honda/values.py
CONFLICT (content): Merge conflict in selfdrive/car/honda/values.py
Auto-merging selfdrive/car/honda/interface.py
Auto-merging selfdrive/car/honda/hondacan.py
CONFLICT (content): Merge conflict in selfdrive/car/honda/hondacan.py
Auto-merging selfdrive/car/honda/carstate.py
Auto-merging selfdrive/car/honda/carcontroller.py
Auto-merging selfdrive/car/gm/interface.py
CONFLICT (content): Merge conflict in selfdrive/car/gm/interface.py
Auto-merging selfdrive/car/gm/carcontroller.py
CONFLICT (content): Merge conflict in selfdrive/car/gm/carcontroller.py
Auto-merging panda/VERSION
CONFLICT (content): Merge conflict in panda/VERSION
Auto-merging opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc
CONFLICT (add/add): Merge conflict in opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc
Auto-merging cereal/car.capnp
CONFLICT (content): Merge conflict in cereal/car.capnp
Auto-merging apk/ai.comma.plus.offroad.apk
CONFLICT (content): Merge conflict in apk/ai.comma.plus.offroad.apk
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
Cadmans-MacBook-Pro:openpilot cadmanchui$ cd ..
Cadmans-MacBook-Pro:~ cadmanchui$ rm -rf ./openpilot
Cadmans-MacBook-Pro:~ cadmanchui$ git clone https://github.com/kegman/openpilot
Cloning into 'openpilot'...
remote: Enumerating objects: 83, done.
remote: Counting objects: 100% (83/83), done.
remote: Compressing objects: 100% (43/43), done.
remote: Total 5608 (delta 56), reused 55 (delta 40), pack-reused 5525
Receiving objects: 100% (5608/5608), 348.76 MiB | 3.38 MiB/s, done.
Resolving deltas: 100% (3250/3250), done.
Cadmans-MacBook-Pro:~ cadmanchui$ cd openpilot
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout -b energee-odyssey-china kegman-odyssey-china
fatal: 'kegman-odyssey-china' is not a commit and a branch 'energee-odyssey-china' cannot be created from it
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout kegman-odyssey-china
Branch 'kegman-odyssey-china' set up to track remote branch 'kegman-odyssey-china' from 'origin'.
Switched to a new branch 'kegman-odyssey-china'
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout -b energee-odyssey-china kegman-odyssey-china
Switched to a new branch 'energee-odyssey-china'
Cadmans-MacBook-Pro:openpilot cadmanchui$ git pull https://github.com/energee/openpilot.git odyssey-china

remote: Enumerating objects: 101, done.
remote: Counting objects: 100% (101/101), done.
remote: Total 173 (delta 101), reused 101 (delta 101), pack-reused 72
Receiving objects: 100% (173/173), 30.78 KiB | 10.26 MiB/s, done.
Resolving deltas: 100% (135/135), completed with 23 local objects.
From https://github.com/energee/openpilot
 * branch            odyssey-china -> FETCH_HEAD
warning: Cannot merge binary files: apk/ai.comma.plus.offroad.apk (HEAD vs. f01c7acd65eeb165dd9870a180c1552077bc0ea4)
Auto-merging selfdrive/controls/lib/alertmanager.py
CONFLICT (content): Merge conflict in selfdrive/controls/lib/alertmanager.py
Auto-merging selfdrive/controls/controlsd.py
CONFLICT (content): Merge conflict in selfdrive/controls/controlsd.py
Auto-merging selfdrive/car/hyundai/values.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/values.py
Auto-merging selfdrive/car/hyundai/interface.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/interface.py
Auto-merging selfdrive/car/hyundai/carstate.py
CONFLICT (content): Merge conflict in selfdrive/car/hyundai/carstate.py
Auto-merging selfdrive/car/honda/values.py
CONFLICT (content): Merge conflict in selfdrive/car/honda/values.py
Auto-merging selfdrive/car/honda/interface.py
Auto-merging selfdrive/car/honda/hondacan.py
CONFLICT (content): Merge conflict in selfdrive/car/honda/hondacan.py
Auto-merging selfdrive/car/honda/carstate.py
Auto-merging selfdrive/car/honda/carcontroller.py
Auto-merging selfdrive/car/gm/interface.py
CONFLICT (content): Merge conflict in selfdrive/car/gm/interface.py
Auto-merging selfdrive/car/gm/carcontroller.py
CONFLICT (content): Merge conflict in selfdrive/car/gm/carcontroller.py
Auto-merging panda/VERSION
CONFLICT (content): Merge conflict in panda/VERSION
Auto-merging opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc
CONFLICT (add/add): Merge conflict in opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc
Auto-merging cereal/car.capnp
CONFLICT (content): Merge conflict in cereal/car.capnp
Auto-merging apk/ai.comma.plus.offroad.apk
CONFLICT (content): Merge conflict in apk/ai.comma.plus.offroad.apk
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
Cadmans-MacBook-Pro:openpilot cadmanchui$ 
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout kegman-odyssey-china
README.md: needs merge
apk/ai.comma.plus.offroad.apk: needs merge
cereal/car.capnp: needs merge
opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc: needs merge
panda/VERSION: needs merge
selfdrive/car/gm/carcontroller.py: needs merge
selfdrive/car/gm/interface.py: needs merge
selfdrive/car/honda/hondacan.py: needs merge
selfdrive/car/honda/values.py: needs merge
selfdrive/car/hyundai/carstate.py: needs merge
selfdrive/car/hyundai/interface.py: needs merge
selfdrive/car/hyundai/values.py: needs merge
selfdrive/controls/controlsd.py: needs merge
selfdrive/controls/lib/alertmanager.py: needs merge
error: you need to resolve your current index first
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi README.md
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add README.md
Cadmans-MacBook-Pro:openpilot cadmanchui$ git remove apk/ai.comma.plus.offroad.apk
git: 'remove' is not a git command. See 'git --help'.

The most similar command is
	remote
Cadmans-MacBook-Pro:openpilot cadmanchui$ git rm apk/ai.comma.plus.offroad.apk
apk/ai.comma.plus.offroad.apk: needs merge
rm 'apk/ai.comma.plus.offroad.apk'
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi cereal/car.capnp
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add cereal/car.capnp
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi panda/VERSION
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add panda/VERSION
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/gm/carcontroller.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/car/gm/carcontroller.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/gm/interface.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/gm/interface.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/car/gm/interface.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/honda/hondacan.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/car/honda/hondacan.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/honda/values.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/car/honda/values.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/hyundai/carstate.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/car/hyundai/carstate.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/hyundai/interface.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/car/hyundai/interface.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/hyundai/values.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/car/hyundai/values.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/car/hyundai/values.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/controls/controlsd.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/controls/controlsd.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/controls/controlsd.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi selfdrive/controls/lib/alertmanager.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git add selfdrive/controls/lib/alertmanager.py
Cadmans-MacBook-Pro:openpilot cadmanchui$ git branch
* energee-odyssey-china
  kegman-devel
  kegman-odyssey-china
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout kegman-odyssey-china
M	README.md
D	apk/ai.comma.plus.offroad.apk
M	opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc
M	panda/VERSION
M	selfdrive/car/gm/interface.py
M	selfdrive/car/honda/carcontroller.py
M	selfdrive/car/honda/carstate.py
M	selfdrive/car/honda/hondacan.py
M	selfdrive/car/honda/interface.py
M	selfdrive/car/honda/values.py
M	selfdrive/car/hyundai/carstate.py
Switched to branch 'kegman-odyssey-china'
Your branch is up to date with 'origin/kegman-odyssey-china'.
Cadmans-MacBook-Pro:openpilot cadmanchui$ git merge --no-ff energee-odyssey-china
Already up to date.
Cadmans-MacBook-Pro:openpilot cadmanchui$ git commit -a
Aborting commit due to empty commit message.
Cadmans-MacBook-Pro:openpilot cadmanchui$ git commit -a
[kegman-odyssey-china 682f8ca] Merge Energee Odyssey-China branch
 11 files changed, 118 insertions(+), 40 deletions(-)
 delete mode 100644 apk/ai.comma.plus.offroad.apk
Cadmans-MacBook-Pro:openpilot cadmanchui$ git branch
  energee-odyssey-china
  kegman-devel
* kegman-odyssey-china
Cadmans-MacBook-Pro:openpilot cadmanchui$ git push origin kegman-odyssey-china
Counting objects: 20, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (19/19), done.
Writing objects: 100% (20/20), 3.07 KiB | 3.07 MiB/s, done.
Total 20 (delta 17), reused 0 (delta 0)
remote: Resolving deltas: 100% (17/17), completed with 17 local objects.
To https://github.com/kegman/openpilot
   2bbbcc5..682f8ca  kegman-odyssey-china -> kegman-odyssey-china
Cadmans-MacBook-Pro:openpilot cadmanchui$ git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), done.
From https://github.com/kegman/openpilot
   682f8ca..5a5b306  kegman-odyssey-china -> origin/kegman-odyssey-china
Updating 682f8ca..5a5b306
Fast-forward
 opendbc/honda_odyssey_extreme_edition_2018_china_can.dbc | 15 ---------------
 1 file changed, 15 deletions(-)
Cadmans-MacBook-Pro:openpilot cadmanchui$ ls
CONTRIBUTING.md			installer
Dockerfile.openpilot		launch_chffrplus.sh
LICENSE				launch_openpilot.sh
Makefile			opendbc
README.md			panda
README_chffrplus.md		phonelibs
RELEASES.md			pyextra
SAFETY.md			requirements_openpilot.txt
apk				run_docker_tests.sh
cereal				selfdrive
common
Cadmans-MacBook-Pro:openpilot cadmanchui$ git checkout kegman-devel
Switched to branch 'kegman-devel'
Your branch is up to date with 'origin/kegman-devel'.
Cadmans-MacBook-Pro:openpilot cadmanchui$ ls
CONTRIBUTING.md			installer
Dockerfile.openpilot		launch_chffrplus.sh
LICENSE				launch_openpilot.sh
Makefile			opendbc
README.md			panda
README_chffrplus.md		phonelibs
RELEASES.md			pyextra
SAFETY.md			requirements_openpilot.txt
apk				run_docker_tests.sh
cereal				selfdrive
common
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi README.me
Cadmans-MacBook-Pro:openpilot cadmanchui$ vi README.md

[![](https://i.imgur.com/UetIFyH.jpg)](#)
  
Welcome to openpilot
======

[openpilot](http://github.com/commaai/openpilot) is an open source driving agent. Currently, it performs the functions of Adaptive Cruise Control (ACC) and Lane Keeping Assist System (LKAS) for selected Honda, Toyota, Acura, Lexus, Chevrolet, Hyundai, Kia. It's about on par with Tesla Autopilot and GM Super Cruise, and better than [all other manufacturers](http://www.thedrive.com/tech/5707/the-war-for-autonomous-driving-part-iii-us-vs-germany-vs-japan).

The openpilot codebase has been written to be concise and to enable rapid prototyping. We look forward to your contributions - improving real vehicle automation has never been easier.

Table of Contents
=======================

* [Community](#community)
* [Hardware](#hardware)
* [Supported Cars](#supported-cars)
* [Community Maintained Cars](#community-maintained-cars)
* [In Progress Cars](#in-progress-cars)
* [How can I add support for my car?](#how-can-i-add-support-for-my-car-)
* [Directory structure](#directory-structure)
* [User Data / chffr Account / Crash Reporting](#user-data-chffr-account-crash-reporting)
* [Testing on PC](#testing-on-pc)
* [Contributing](#contributing)
* [Licensing](#licensing)

---

Community
------

openpilot is developed by [comma.ai](https://comma.ai/) and users like you.

We have a [Twitter you should follow](https://twitter.com/comma_ai).

Also, we have a several thousand people community on [slack](https://slack.comma.ai).

<table>
  <tr>
    <td><a href="https://www.youtube.com/watch?v=9TDi0BHgXyo" title="YouTube" rel="noopener"><img src="https://i.imgur.com/gBTo7yB.png"></a></td>
    <td><a href="https://www.youtube.com/watch?v=1zCtj3ckGFo" title="YouTube" rel="noopener"><img src="https://i.imgur.com/gNhhcep.png"></a></td>
    <td><a href="https://www.youtube.com/watch?v=Qd2mjkBIRx0" title="YouTube" rel="noopener"><img src="https://i.imgur.com/tFnSexp.png"></a></td>
"README.md" 220L, 16944C
