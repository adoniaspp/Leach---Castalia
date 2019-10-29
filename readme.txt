Steps to install the LEACH

1. Intall Omnet-4.x

2. Install Castalia-3.2

3. Copy the file adjustmentFile.patch to the Castalia folder. E.g. home/user/Castalia-3.2 

4. Open the prompt, go to the Castalia folder and type the following command: patch -p0 -i adjustmentFile.patch

5. Copy the folder leachRouting to the following path Castalia-3.2/src/node/communication/routing/

6. Copy the folder leach to the following path Castalia-3.2/Simulations/

7. Type ./makemake

8. Type make

9. Go to the path Castalia-3.2/Simulations/leach and type the following command: Castalia -i leach.ini -c General

10.  Enjoy :)
