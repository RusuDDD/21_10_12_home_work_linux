   0 cd /home
   1 cd ..
   2 cd /home
   3 mkdir -p /home/animals/cats/garfield.txt
   4 mkdir -p /home/animals/dogs/pluto.txt
   5 mkdir -p /home/animals/fish/nemo.txt
   6 mkdir -p /home/humans
   7 mkdir -p /tmp/adam.txt
   8 cp -R ../tmp/adam.txt humans
   9 tree
  10 mkdir -p /tmp/evA.txt
  11 rm ../tmp/evA ../opt/eve.txt
  12 rm ../tmp/evA opt/eve.txt
  13 rm ../tmp/evA.txt ../opt/eve.txt
  14 rm ../tmp/evA.txt opt/eve.txt
  15 rm ../tmp/evA.txt /opt/eve.txt
  16 rm ../tmp/evA.txt ../opt/eve.txt
  17 mv ../tmp/evA.txt humans
  18 tree
  19 ls -la /humans
  20 ls -la humans
  21 history > /history.txt
  22 history > /tmp/history.txt
