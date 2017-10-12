<h3>Datacoin-Bootstrap</h3>


bootstrap.dat allows a new Datacoin client to rapidly import the initial blocks from a local file instead of slowly downloading blocks from random peers. This significantly reduces the time it takes to get a client synced with the current blockchain.

Regardless of your operating system use the following steps to make use of the bootstrap.dat file:

1.Download bootstrap.dat.gz OR bootstrap.dat.zip from github or mirrors. 
2.Decompress to obtain bootstrap.dat. 
3.Put it into the Datacoin datadir. This is the same folder that contains wallet.dat and the blocks folder.

Linux: Datacoin's data directory is located in ~/.datacoin/ by default. You can run ls -a to see directories that start with a dot. You can also search for the directory with the following command: find / -name wallet.dat -print 2>/dev/null

Windows: Go to Start>Run (or press WinKey+R) and run: explorer %APPDATA%\Datacoin Datacoin's data directory will open. "AppData" and "Application Data" are hidden by default in Windows.

