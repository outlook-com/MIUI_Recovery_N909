1 the project is build android recovery only;

2 before building, make sure copy project <b>android_prebuilt</b>,<del> <b>android_bionic</b></del> and <b>anroid_hardware</b> to the directory ,which from ICS or higher 

3 Steps as following:
 <code>
    $. build/envsetup.sh
    $make crespo
</code>
  please see the out/patch_device/crespo/ , find recovery.img
 
4 please check Makefile to obtain the supported devices;

 
<h1><ins>Modified by sndnvaps@gmail.com </ins></h1>



[http://www.gaojiquan.com](http://www.gaojiqu.com "Gaojiquan.com") 

<h1>2013/4/12 </h1>

<h2> Changelog :</h2> 

    <h2> support : ZTE n909 </h2>
<p>     
Setps to build n909 :

      <code>
          # build/envsetup.sh
          # make n909 
      </code>

You cand find recovery.img in folder out/patch_device/n909 

</p>

<h1> Get the android_bionic </h1>
    <code>
    $ cd MIUI_Recovery_N909 
    $ git submodule init 
    $ git submodule update 
   </code>


