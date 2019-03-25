
starver dev
cvs co OnlTools/Jevp
cons
OnlTools/Jevp/launch trgBuilder -file /direct/star+u/msimko/ZDC/online/daq/st_physics_adc_17035003_raw_3000003.daq -pdf output2016.pdf

# Chces se divat jen do StJevpBuilders
# Uvnitr je trgBuilder.h a trgBuilder.cxx

# Potom, co mas vse znovu zkompilovane a vyzkousene
cvs commit OnlTools/Jevp/StJevpBuilders/trgBuilder.cxx -m "zprava"
# Potom napsat Jeffovi na jml@bnl.gov, aby tvuj builder znovu zkompiloval
