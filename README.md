julien@julien-Lenovo-ideapad-530S-15IKB:~/quetes/shell/planets/real$ tree
.
├── gas-giants
│   ├── jupiter.jpeg
│   ├── neptune.jpeg
│   ├── saturn.jpeg
│   └── uranus.jpeg
└── telluric
    ├── earth.jpeg
    ├── mars.jpeg
    ├── mercury.jpeg
    └── venus.jpeg

2 directories, 8 files


wget https://github.com/bhubr/bhubr.github.io/raw/master/wild/planets.zip
  109  unzip planets.zip
  111  cd ~/quetes/shell/planets
  112  mkdir real
  113  mkdir fictional
  114  mkdir inhabited
  115  mkdir real/telluric
  116  mkdir real/gas-giants
  117  mkdir real/dwarf-planets
  120  mv mercury.jpeg venus.jpeg earth.jpeg mars.jpeg jupiter.jpeg saturn.jpeg uranus.jpeg neptune.jpeg pluto.jpeg real/
  121  mv arrakis.jpeg coruscant.jpeg cybertron.jpeg fictional/
  122  cp real/earth.jpeg inhabited/
  123  cp fictional/arrakis.jpeg fictional/coruscant.jpeg fictional/cybertron.jpeg inhabited/
  124  cd ~/quetes/shell/planets/real
  125  mv mercury.jpeg venus.jpeg earth.jpeg mars.jpeg telluric/
  126  mv jupiter.jpeg saturn.jpeg uranus.jpeg neptune.jpeg gas-giants/
  127  mv pluto.jpeg dwarf-planets/
  128  rm -r dwarf-planets
  129  tree
  130  history
