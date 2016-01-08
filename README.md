# bin
IDAPython binaries for various releases of IDA.

6.9 binaries, 2015 01 08
------------------------
Windows:
idasdk69\plugins\idapython>python build.py --with-hexrays --swig-bin ...\third_party\swig\swigwin-2.0.12\swig.exe --swig-inc ...\third_party\swig\swigwin-2.0.12\Lib\python;...\third_party\swig\swigwin-2.0.12\lib

Linux:
idasdk69/plugins/idapython$ python build.py --with-hexrays --python-home /opt/Python-2.7.7-32bit-install-UCS4/ --swig-bin .../third_party/swig/swiglinux-2.0.12/swig-2.0.12-install/bin/swig --swig-inc .../third_party/swig/swiglinux-2.0.12/swig-2.0.12-install/share/swig/2.0.12/python/:.../third_party/swig/swiglinux-2.0.12/swig-2.0.12-install/share/swig/2.0.12/

Mac:
.../idasdk69/plugins/idapython$ python build.py --with-hexrays --swig-bin .../third_party/swig/swigmac-2.0.12/swig-2.0.12-install/bin/swig --swig-inc .../third_party/swig/swigmac-2.0.12/swig-2.0.12-install/share/swig/2.0.12/python/:.../third_party/swig/swigmac-2.0.12/swig-2.0.12-install/share/swig/2.0.12/
