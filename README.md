### Mini Project : การศึกษาปัจจัยที่มีผลกระทบต่อการผลิตรถยนต์สันดาปในภูมิภาค Asia
สำหรับ Mini-project นี้ จะประกอบไปด้วยการนำเสนอ 4 ส่วน ด้วยกัน ดังนี้

Part 1: ภาพรวมการผลิตรถยนต์สันดาปทั่วโลก ตั้งแต่ปี 2014-2023 โดยประกอบด้วยภูมิภาคดังนี้ 
ภูมิภาคเอเชีย ภูมิภาคอเมริกา ภูมิภาคยุโรปตะวันตก ภูมิภาคยุโรปกลางและตะวันออก ภูมิภาคตะวันออกกลาง 
จะแสดงจำนวนการผลิตรถรายปี จำนวนการผลิตรถรายภูมิภาค สัดส่วนการผลิตรถเทียบแต่ละ segment เป็นต้น

Part 2: ภาพรวมการผลิตรถยนต์สันดาปในภูมิภาคเอเชีย ตั้งแต่ปี 2014-2023
จะเป็นข้อมูลแสดงสัดส่วนจำนวนการผลิตรายประเทศแบ่งตาม segment รวมถึง insgiht ที่พบสำหรับบาง segment

Part 3: การศึกษาปัจจัยที่มีผลกระทบต่อการผลิตรถยนต์ในโซน Asia โดยศึกษาปัจจัยเพิ่มเติมที่มีผลต่อยอดการผลิตรถยนต์

Part 4: การคาดการณ์ปริมาณการผลิตรถยนต์ในภูมิภาค Asia



### Part 1: ภาพรวมการผลิตรถยนต์สันดาปทั่วโลก
จากข้อมูลฐานการผลิตรถยนต์ทั่วโลก จะแบ่งเป็น 5 ภูมิภาค โดยในแต่ละภูมิภาคประกอบประเทศต่างๆ ดังนี้

![image](https://github.com/user-attachments/assets/5bdcbe1b-942e-4891-bc36-794af44d34b7)

และในส่วนข้อมูลรถยนต์จะจัดเป็น group segment และกลุ่ม segment ย่อย ดังนี้

![image](https://github.com/user-attachments/assets/88deebbd-e10b-49ed-9ef0-7c6f2fbfa31d)

  ถัดมาจะเป็นข้อมูลจำนวนการผลิตรถยนต์ตั้นแต่ปี 2014-2023 ซึ่งจะมีค่าเฉลี่ยในการผลิตรถยนต์รวมทั้งหมดอยู่ที่ 87.11 ล้านคันต่อปี จากกราฟที่ 1 จะแสดงยอดการผลิตรถยนต์รายปี และแสดงตามภูมิภาคของการผลิต โดยจะเห็นว่าในปี 2020 และ 2021 มียอดการผลิตที่ต่ำลง เนื่องจากเป็นช่วงสถานการณ์ Covid-19 และในปี 2023 จะเห็นว่า มีจำนวนการผลิตกลับมาเพิ่มขึ้นใกล้เคียงกับปี 2019 (ช่วงก่อนสถานการณ์ Covid-19) ซึ่งมียอดการผลิตรถยนต์อยู่ที่ 89.21 ล้านคัน ที่สูงกว่าค่าเฉลี่ยในการผลิตรถยนต์

![figure_1](https://github.com/maxvcbhan/DADS5001-car-production/blob/main/figure/figure1_car_production_by_region.png "กราฟที่ 1 แสดงจำนวนการผลิตรถยนต์ปี 2014-2023 แบ่งตามภูมิภาคการผลิต")

<p align="center"> กราฟที่ 1 แสดงจำนวนการผลิตรถยนต์ปี 2014-2023 แบ่งตามภูมิภาคการผลิต
  
  ถัดมาจะเป็นข้อมูลการผลิตรถยนต์แยกตามภูมิภาค จะเห็นว่า ภูมิภาค Asia มีค่าเฉลี่ยการผลิตรถอยู่ที่ 48.22 ล้านคันต่อปี คิดเป็น 55% ของค่าเฉลี่ยรวมทั้งหมดของทุกภูมิภาค และห่างจากอันดับที่ 2 คือ ภูมิภาค America ที่มีค่าเฉลี่ยการผลิตรถอยู่ที่ 19.11 ล้านคันต่อปี ซึ่งจำนวนการผลิตรถของ Asia มากกว่า เกือบ 4 เท่าของจำนวนการผลิตของภูมิภาค America (ข้อมูลตามกราฟที่ 2)

<p align="center"> กราฟที่ 2 แสดงข้อมูลการผลิตรถยนต์แยกตามภูมิภาค  (**ไม่ใช่ค่าเฉลี่ยนะ หัวกราฟใน excel ตัด average ออก)

  ที่นี้มาดูข้อมูลสัดส่วนการผลิตรถยนต์รายปี แบ่งตามภูมิภาค จะเห็นว่า สัดส่วนการผลิตรถในภูมิภาค Asia มีสัดส่วนที่สูงขึ้นเรื่อยๆ จากปี 2014 ที่มีสัดส่วนอยู่ที่ 53% จนมาถึงปี 2023 ที่มีสัดส่วนอยู่ที่ 60% เพิ่มขึ้นมา 7% ซึ่งจะมาจากการผลิตของภูมิภาค Europe ที่ลดลง (ข้อมูลตามกราฟที่ 3)

<p align="center"> กราฟที่ 3 แสดงข้อมูลสัดส่วนการผลิตรถยนต์รายปี เปรียบเทียบตามภูมิภาค

  ถัดมาจะไปดูวิเคราะห์ในมุมของ group segment กันบ้าง จากกราฟที่ 4 จะแสดงสัดส่วนการผลิตรถยนต์ จะเห็นว่า รถยนต์ Passenger มีสัดส่วนสูงที่สุดที่ 42% และรถ SUV จะมีสัดส่วนรองลงมาอยู่ที่ 33%

<p align="center"> กราฟที่ 4 แสดงสัดส่วนการผลิตรถยนต์ แบ่งตาม group segment
  
  ทีนี้ถ้าวิเคราะห์ดูแนวโน้มของรถยนต์แต่ละ group segment รายปี ตั้งแต่ปี 2014-2023 จะเห็นว่า สัดส่วนของรถ Passenger นั้น จะมีแนวโน้มที่ลดลงจาก 52% (ปี 2014) เป็น 42% (ปี 2023) และในส่วนของรถยนต์ SUV จะเป็นที่นิยมมากยิ่งขึ้น โดยจะเห็นว่าตั้งแตปี 2019 สัดส่วนของรถ SUV จะมีเปอร์เซ็นต์สูงกว่าค่าเฉลี่ยที่ 33% และเพิ่มมากขึ้นในทุกปี ซึ่งมาจากหลายๆปัจจัย เช่น ความต้องการรถยนต์ที่สามารถใช้งานได้ทั้งในเมืองและนอกเมือง ความสะดวกสบายที่มากกว่า ความรู้สึกปลอดภัย เนื่องจาก SUV มีขนาดใหญ่และสูงกว่า passenger เป็นต้น (ข้อมูลตามกราฟที่ 5)

<p align="center"> กราฟที่ 5 แสดงสัดส่วนการผลิตรถยนต์แต่ละ group segment รายปี

  หากวิเคราะห์ลึกลงไปในกลุ่มย่อยของแต่ละ group segment จะเห็นว่า สัดส่วนของรถ SUV Segment ที่เป็น SUV-C และ SUV-D ที่เป็นรถยนต์ SUV ขนาดกลางถึงขนาดใหญ่ เป็นที่นิยมมากขึ้น โดยจะเห็นจาก สัดส่วนการผลิตที่เพิ่มขึ้นเป็นเท่าตัวในทั้ง 2 Segment (ข้อมูลตามกราฟที่ 6)

  <p align="center"> กราฟที่ 6 แสดงสัดส่วนการผลิตรถยนต์แต่ละกลุ่มย่อยของแต่ละ group segment รายปี 

    จากข้อมูลทั้งหมดข้างต้น สรุปได้ว่า ภูมิภาค Asia มีจำนวนการผลิตยนต์มากที่สุด รองลงมาจะเป็นภูมิภาคอเมริกา ส่วนในมุมของ group segment จะผลิต passenger car มากที่สุด รองลงมาจะเป็น SUV car ในมุมของแนวโน้มการผลิตรถยนต์ สัดส่วนของการผลิตรถ Passenger มีแนวโน้มลดลง ในขณะที่สัดส่วนของการผลิตรถ SUV มีแนวโน้มเพิ่มมากขึ้น
  

### Part 2: ภาพรวมการผลิตรถยนต์สันดาปในภูมิภาคเอเชีย
  เนื่องจากจำนวนการผลิตรถยนต์มากที่สุดในภูมิภาคเอเชีย มีสัดส่วนการผลิตอยู่ที่ 55% จากจำนวนการผลิตทุกภูมิภาค โดยเป็นยอดการผลิตรถยนต์จำนวน 48 ล้านคัน (ข้อมูลตามกราฟที่ 7 วงกลม)


  <p align="center"> กราฟที่ 7 แสดงจำนวนการผลิตรถยนต์แบ่งตามภูมิภาค   

  ถัดมาวิเคราะห์ในมุมของประเทศที่อยู่ภายในภูมิภาคเอเชียกันบ้าง จากกราฟที่ 8 แสดงยอดการผลิตรถยนต์โดยรวมตั้งแต่ปี 2014-2023 จะเห็นว่า ประเทศจีนเป็นประเทศที่มียอดการผลิตรถยนต์เป็นอันดับ 1 มียอดการผลิตอยู่ที่ 267 ล้านคัน คิดเป็นสัดส่วน 55% รองลงมาเป็นประเทศญี่ปุ่น และอินเดีย คิดเป็นสัดส่วน 18% และ 10% ตามลำดับ โดยประเทศไทยจะมียอดการผลิตเป็นอันดับ 4 คิดเป็นสัดส่วนที่ 8% (ข้อมูลตามกราฟที่ 8)


    <p align="center"> กราฟที่ 8 แสดงจำนวนการผลิตรถยนต์แต่ละประเทศ ภายในภูมิภาค Asia
  
    จากข้อมูลสัดส่วนของการผลิตรถยนต์ในแต่ละประเทศจะเห็นว่า ประเทศจีน อินเดีย และอินโดนีเซีย จะมีสัดส่วนของการผลิตรถยนต์ประเภท Unclassified เป็นสัดส่วนที่สูงประมาณ 20% เนื่องจากประเทศเหล่านี้เป็นประเทศที่มีจำนวนประชากรเยอะ จำนวนยี่ห้อในการผลิตรถยนต์ที่เป็นยี่ห้อท้องถิ่น มีจำนวนที่สูง จึงทำให้สัดส่วนของการผลิตรถประเภท Unclassified มีสัดส่วนที่สูงกว่าประเทศอื่นๆ และในมุมของประเทศไทยเป็นประเทศที่มีสัดส่วนในรถ Pickup สูงที่สุด เนื่องจากเป็นฐานการผลิตรถ Pickup ทั้งในประเทศและส่งออก ส่วนประเทศอินโดนีเซีย มีสัดส่วนของรถยนต์ประเภท MPV สูงที่สุดถึง 41% (ข้อมูลตามกราฟที่ 9)

    <p align="center"> กราฟที่ 9 แสดงจำนวนการผลิตรถยนต์แต่ละประเทศ แบ่งตาม group segment

    








  
