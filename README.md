# ressources

eos quota ls /eos/experiment/fcc/

┏━> Quota Node: /eos/experiment/fcc/
┌──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┐
│group     │used bytes│logi bytes│used files│aval bytes│aval logib│aval files│ filled[%]│vol-status│ino-status│
└──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┘
 project     491.03 TB  245.52 TB     2.26 M  600.00 TB  300.00 TB     4.00 M    81.84 %         ok         ok 
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛


description of the ressources for FCC (disk and CPU)

LHE FCC       2.8 10^9 events for a size of 510GB

DELPHES FCC   1.5 10^9 events for a size of 64622GB (64TB)


LHE HE-LHC    0.9 10^9 events for a size of 142GB

DELPHES HE-LHC 1.2 10^9 events for a size of 26585GB (26TB)


FCCSIM v03    0.5 10^9 events for a size of 40591GB (40TB)

FCCSIM v03 ECAL 24 10^6 events for a size of 90707GB (90TB)

USERS 24TB, mostly by few
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
│group     │used bytes│logi bytes│used files│aval bytes│aval logib│aval files│ filled[%]│vol-status│ino-status│
└──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┘
 daemon            0 B        0 B          0        0 B        0 B          0   100.00 %    ignored    ignored 
 def-cg        6.57 TB    3.28 TB     3.68 K        0 B        0 B          0   100.00 %    ignored    ignored 
 nobody            0 B        0 B          0        0 B        0 B          0   100.00 %    ignored    ignored 
 sf           60.20 KB   30.10 KB          1        0 B        0 B          0   100.00 %    ignored    ignored 
 z2           12.70 TB    6.35 TB    21.51 K        0 B        0 B          0   100.00 %    ignored    ignored 
 zf            1.39 TB  694.58 GB    22.49 K        0 B        0 B          0   100.00 %    ignored    ignored 
 zh            1.80 TB  901.20 GB     2.42 K        0 B        0 B          0   100.00 %    ignored    ignored 
 zp            2.48 TB    1.24 TB    26.84 K        0 B        0 B          0   100.00 %    ignored    ignored 

┌──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┐
│summary   │used bytes│logi bytes│used files│aval bytes│aval logib│aval files│ filled[%]│vol-status│ino-status│
└──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┘
 All users    24.94 TB   12.47 TB    76.94 K   60.00 TB   30.00 TB     5.18 M    41.57 %         ok         ok 
 All groups   24.94 TB   12.47 TB    76.94 K        0 B        0 B          0   100.00 %    ignored    ignored 
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
