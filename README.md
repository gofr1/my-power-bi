# my-power-bi

## To put file into git

###  Move and rename file extension to zip
mv report-name.pbix report-name.zip

### Unzip file to some directory
unzip report-name.zip -d dir-name

## To re-create pbix file 

### Zip all files inside directory
cd dir-name
zip -r0 report-name.zip * 

### Move and rename file extension to pbix
mv report-name.zip report-name.pbix
