## Gran Turismo 7 Assets

~63,000 files extracted from gt01.vol - gt99.vol

|               | type          | uses
|---------------|---------------|---------------------------
|   11,859      | .jpg files    | scapes, used car dealership preview images
|   10,328      | .img files    | car images, brand logos
|   3,101       | .txt files    | scapes data/instructions
|   1,369       | .json files   | race parameters, dealership data, livery info, course spots
|   543         | .png files    | track thumbnails

--------

### Workflow

1. Get a fake pkg of Gran Turismo 7
2. Open the pkg file with PS4 PKG Tool
3. Inside the `contents/` folder of the pkg, extract `gt.idx` and each of the `gtXX.vol` files
4. Use GTToolSharp to unpack each of the `gtXX.vol` packages
5. Once extracted, use TXS3Converter to convert any `.img` files to useable `.png` files


--------

### Cars

Grouped into folders by manufacturer number. Inside each folder will have subfolders for specific cars. Not sure how the ID works yet. Inside this subfolder will be a bunch of `.img` files for transparent car thumbnails, and some `.jpg` files for the car when it's in the used car dealership. 

Use Nenkai's TXS3Converter to convert files to useable `.png` format

| manufacturer id   |                   |
| ---------------   | ---------------   
|   0001            | mazda            
|   0002            | ford            
|   0003            | nissan            
|   0004            | toyota            
|   0005            | honda            
|   0006            | suzuki            
|   0007            | bmw            
|   0008            | jaguar            
|   0010            | alfa romeo            
|   0011            | daihitsu            
|   0012            | mitsubishi            
|   0013            | re amemiya            
|   0015            | tvr            
|   0020            | subaru            
|   0021            | pontiac            
|   0022            | corvette            
|   0023            | alpine            
|   0024            | fiat            
|   0025            | peugeot            
|   0026            | -            
|   0037            | -            
|   0042            | -            
|   0043            | -            
|   0044            | -            
|   0050            | -            
|   0051            | -            
|   0053            | -            
|   0057            | -            
|   0062            | -            
|   0070            | -            
|   0071            | -            
|   0077            | -            
|   0080            | -            
|   0083            | -            
|   0085            | -            
|   0095            | -            
|   0107            | -            
|   0118            | -            
|   0140            | -            
|   0141            | -            
|   0144            | -            
|   0178            | -            
|   0180            | -            
|   0188            | -            
|   0225            | -            
|   0228            | -            
|   0229            | -            
|   0231            | -            
|   0236            | -          
|   0239            | -
|   0241            | -            
|   0246            | -           
|   0253            | -          
|   0258            | -     
|   0305            | -        

