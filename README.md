# Gerber-to-G-Code-Conversion
# Name: Sri Vignesh
# Reg No: 212223040204
# Aim
To convert the Gerber File into G-Code using Copper CAM.
# Software required
Copper CAM
# Procedure
1. Open your Gerber file (File → Open → New circuit)</br>
2. Open your Drill file (File → Open → Drill)</br>
3. Match the drill file and engraving file if not matched </br>
4. Right click the pad and set define as pad and then Right click and select edit all identical pads as set the drill size as 0.8mm,1mm.</br>
5. Open your Cutting file (File → Open → Additional Layer and load your cutting file</br>
6. Go to file/Orgin and set x=0,y=0 </br>
7. Go to file/offset and select the option shift manually</br>
8. Select the layer 6 and move the cutting file and set the border</br>
9. Go to parameter/ tool library and check the identifaication and specification</br>
10. Go to parameter/selected tool and check the engraving tool, cutting tool and drill tool</br>
11. Go to machine/ Contours/calculate Contours</br>
12. Go to machine/mill and select engraving you will get the g code,similarly for Drill and cut. </br>
13. Save the G code</br>
# Contours Output
![WhatsApp Image 2024-05-15 at 23 40 07_73bd4e21](https://github.com/SriVignesh-G/Gerber-to-G-Code-Conversion/assets/147576510/355a4323-d441-4cc4-8d4e-0e00cd081ae6)


# G Code
### Engraving G Code
![Screenshot 2024-05-15 234805](https://github.com/SriVignesh-G/Gerber-to-G-Code-Conversion/assets/147576510/9a2a00e8-7b81-4995-a77d-25cc8a87b137)
![Screenshot 2024-05-15 234825](https://github.com/SriVignesh-G/Gerber-to-G-Code-Conversion/assets/147576510/a196a20c-b118-49c4-aa47-52afb26116d4)


### Drill_0.8 G Code
![Screenshot 2024-05-15 235003](https://github.com/SriVignesh-G/Gerber-to-G-Code-Conversion/assets/147576510/1b0172a1-b482-4f4b-8c8e-e1458fa098f7)

### Drill 1.0 G Code
![Screenshot 2024-05-15 235056](https://github.com/SriVignesh-G/Gerber-to-G-Code-Conversion/assets/147576510/930f66df-0d08-4160-8e5d-08457e4b1389)
![Screenshot 2024-05-15 235105](https://github.com/SriVignesh-G/Gerber-to-G-Code-Conversion/assets/147576510/9ab8dd7a-90e1-4e94-afb0-6ed40de42ed7)


### Cutting G Code
![Screenshot 2024-05-15 235138](https://github.com/SriVignesh-G/Gerber-to-G-Code-Conversion/assets/147576510/74cd027e-e157-466a-96f0-fd2d0bd2801f)



# Result

Thus the Gerber File into G-Code using Copper CAM.
