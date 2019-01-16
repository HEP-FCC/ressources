# ressources
=====

DISK
------------
description of the ressources for FCC (disk and CPU)

LHE FCC       2.8 10^9 events for a size of 510GB

LHE HE-LHC    0.9 10^9 events for a size of 142GB


DELPHES FCC   1.5 10^9 events for a size of 64622GB (64TB) (0.064MB/evt)

DELPHES HE-LHC 1.2 10^9 events for a size of 26585GB (26TB)


FCCSIM v03    0.5 10^9 events for a size of 40591GB (40TB) (0.08MB/evt)

FCCSIM v03 ECAL 2.4 10^7 events for a size of 90707GB (90TB) (3.8MB/evt)

USERS 24TB, mostly by few


CPU
------------
For LHE, very quick in general (because LO) 10-1000 events/min
For FCCPhys, standard, but can take long and become very inefficient with matching 30-70 events/min (take 50 as averaged value)
For simulation, vary really with the type of detector and particle and energy between 20 and 0.15 events/min (take 2 as averaged value)



Predictions
------------
Assuming the numbers above have been produced in a 6 months period (180days) (this is possible as previous productions are removed regularly)
it means we can produce

 1) 10^7 physics events per day (2 10^9events/180days) which represents 0.64TB/day and 2 10^5 mins of CPU/day
 
 2) 2.5 10^6 full sim events per day which represents 0.2TB/day and 10^6 mins of CPU/day
 
 3) 10^5 large full sim events per day which represents 0.38TB/day and 5 10^4 mins of CPU/day
and assuming 50TB can be removed every 6 months

sum 1)+2)+3) 
1.22TB/day
1.25 10^6 mins of CPU/day (2600 jobs on 8nh like queues)


EOS STATUS
------------

~~~{.sh}
eos quota ls /eos/experiment/fcc/

┏━> Quota Node: /eos/experiment/fcc/
┌──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┐
│group     │used bytes│logi bytes│used files│aval bytes│aval logib│aval files│ filled[%]│vol-status│ino-status│
└──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┘
 project     491.03 TB  245.52 TB     2.26 M  600.00 TB  300.00 TB     4.00 M    81.84 %         ok         ok 
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
~~~

~~~{.sh}
eos quota ls /eos/experiment/fcc/users/

┏━> Quota Node: /eos/experiment/fcc/users/
┌──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┐
│user      │used bytes│logi bytes│used files│aval bytes│aval logib│aval files│ filled[%]│vol-status│ino-status│
└──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┘
 50836         1.38 GB  688.65 MB          7  200.00 GB  100.00 GB    10.00 K     0.69 %         ok         ok 
 90030         5.93 TB    2.96 TB     1.43 K        0 B        0 B          0   100.00 %    ignored    ignored 
 93549        95.85 GB   47.92 GB         14        0 B        0 B          0   100.00 %    ignored    ignored 
 95964       166.86 GB   83.43 GB         23  200.00 GB  100.00 GB    10.00 K    83.43 %         ok         ok 
 97088       436.00 KB  218.00 KB          9  200.00 GB  100.00 GB    10.00 K     0.00 %         ok         ok 
 akolano       1.54 TB  770.36 GB     3.12 K    2.00 TB    1.00 TB    10.00 K    77.04 %         ok         ok 
 azaborow     12.70 TB    6.35 TB    21.51 K   15.00 TB    7.50 TB    50.00 K    84.70 %         ok         ok 
 cbern             0 B        0 B          1  200.00 GB  100.00 GB    10.00 K     0.00 %         ok         ok 
 cneubuse      1.39 TB  694.58 GB    22.49 K   10.00 TB    5.00 TB          0    13.89 %         ok    ignored 
 daemon            0 B        0 B          0        0 B        0 B          0   100.00 %    ignored    ignored 
 eperez      734.30 GB  367.15 GB     1.51 K  200.00 GB  100.00 GB    10.00 K   100.00 %   exceeded         ok 
 helsens     747.44 GB  373.72 GB     6.07 K   10.00 TB    5.00 TB    10.00 K     7.47 %         ok         ok 
 jhrdinka      6.19 GB    3.10 GB        832   10.00 TB    5.00 TB          0     0.06 %         ok    ignored 
 kojin             0 B        0 B          0  200.00 GB  100.00 GB    10.00 K     0.00 %         ok         ok 
 nobody            0 B        0 B          0        0 B        0 B          0   100.00 %    ignored    ignored 
 novaj       776.81 GB  388.41 GB    19.65 K   10.00 TB    5.00 TB     5.00 M     7.77 %         ok         ok 
 selvaggi      1.88 MB  940.19 KB          1  200.00 GB  100.00 GB    10.00 K     0.00 %         ok         ok 
 solans            0 B        0 B          0  200.00 GB  100.00 GB    10.00 K     0.00 %         ok         ok 
 sznajder          0 B        0 B          0  200.00 GB  100.00 GB    10.00 K     0.00 %         ok         ok 
 toprice           0 B        0 B          0  200.00 GB  100.00 GB    10.00 K     0.00 %         ok         ok 
 voutsina    849.45 GB  424.72 GB        274    1.00 TB  500.00 GB    10.00 K    84.94 %         ok         ok 
 

┌──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┐
│summary   │used bytes│logi bytes│used files│aval bytes│aval logib│aval files│ filled[%]│vol-status│ino-status│
└──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┘
 All users    24.94 TB   12.47 TB    76.94 K   60.00 TB   30.00 TB     5.18 M    41.57 %         ok         ok 
 All groups   24.94 TB   12.47 TB    76.94 K        0 B        0 B          0   100.00 %    ignored    ignored 
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
~~~
