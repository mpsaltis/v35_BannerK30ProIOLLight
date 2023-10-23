# v35_BannerK30ProIOLLight

## Add ENUMs to CODESYS Project

1. Add a new Enumeration the the CODESYS Project. Copy the plain text from the enumerations from /enums. Repeat this for K30ProAnimationSpeed, K30ProAnimationsType, K30ProColor and K30ProIntensity

   ![image](https://github.com/mpsaltis/v35_BannerK30ProIOLLight/assets/90796089/e554b8fd-7c01-4ed8-bf8e-82fd7051bc3c)


## FB Instantiation

2. Create a new instance of a function block. copy plainST_fb_Banner_K30Pro into the ST editor to create the function block
3. Instanciate an instace of the function block (Shown below in CFC)

![image](https://github.com/mpsaltis/v35_BannerK30ProIOLLight/assets/90796089/76ef7715-16a8-444a-b271-ec2e7f1a94f9)

## IO Mapping to 765-4301

4. In this example the K30Pro is connected to a WAGO 765-4301 IO Link Master. The data is read by the PLC via EthernetIP and mapped into the inputs of the function block.
   
![image](https://github.com/mpsaltis/v35_BannerK30ProIOLLight/assets/90796089/7ff20d3c-8aa1-4b43-b569-cb78d730c51e)
