gatherfdpdim_all -- gather files from fast_dp and dimple runs with all HKL
usage:
    gatherfdpdim --help      print this message
    gatherfdpdim             gather from current directory and below
    gatherfdp projectdir     gather from projectdir and below
 creates ./fast_dp_dir /fast_dp_dir/XDS and ./dimple_dir
 looks for fast_dp.log, fast_dp.mtx, final.mtz, final.pdb, screen.log
           XDS_ASCII.HKL, INTEGRATE.HKL
 and puts the first two into fast_dp_dir, the next three into dimple_dir,
           and the two HKL files into fast_dp_dir/XDS
 naming the files by full path names with any embedded solidus changed
 to hyphens
