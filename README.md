# Final_project_MobilePrograming-S3

## Project UAS
```
Nama            : Raja Happyanto
Kelas           : TI.22.A2
NIM             : 312210235
Dosen Pengampu  : Donny Maulana, S.Kom., M.M.S.I
Mata Kuliah     : Pemrograman Mobile (UAS)
```

## Isi Program 
- Fibonacci
- Scroll Sianida
- Alarm
- Chat
- Maps
- Fragment
- Launcer spash
## Demo Video Aplikasi, di jalankan pada Peramgkat Xiaomi

## Laporan Project (PDF)

## Tampilan Aplikasi Dahbord
![Screenshot_2024-01-17-13-20-12-230_com example RajaUAS](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/90754789-6b35-4679-aee0-4de90740e6db)


## 1. Splash
```
code and design
```
![Screenshot (133)](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/83eddca3-bbe3-4c1b-8163-7e815c8eefa5)

### Output
![Screenshot_2024-01-17-13-20-05-644_com example RajaUAS](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/8cdce420-2ee7-4938-94a9-a3c105ee34fc)

## 2. Fibonacci
```
code and design
```
![Screenshot (136)](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/440fb2d6-8329-4f90-92ad-45d0691fcd61)

### Output
![Screenshot_2024-01-17-13-22-10-411_com example RajaUAS](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/0361ed09-3dd8-4cae-9f1f-c3f9e1d3e786)

## 3. Scroll Sianida
```
code and design
```
![Screenshot (134)](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/62773a1b-13c5-44ee-bbaa-615edf6cf0c0)

### Output
![Screenshot_2024-01-17-13-21-57-761_com example RajaUAS](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/a93b5311-eaf3-46f7-bddd-66180af51240)

## 4. Alarm
```
code 
```
```
        buttonAlarm.setOnClickListener(v -> {
            Intent intent = new Intent(AlarmClock.ACTION_SHOW_ALARMS);
            startActivity(intent);
        });
```
### Output
![Screenshot_2024-01-17-13-21-24-603_com android deskclock](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/4ffd6fc9-f9bd-48d8-81f8-8dbd9667c54b)

## 5. Chat
```
code and design
```
![Screenshot (135)](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/787e74e4-a6b6-4704-b680-2329349bcd0b)

### Output
![Screenshot_2024-01-17-13-20-57-909_com example RajaUAS](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/c0bb1ec4-3f96-4243-836f-a8ee8ac67ce4)

## 6. Maps
```
code 
```
```
        buttonMaps.setOnClickListener(v -> {
            Intent intent = new Intent(Intent.ACTION_VIEW, Uri.parse("https://www.google.com/maps/place/UNIVERSITAS+PELITA+BANGSA/@-6.3246424,107.1690454,14z/am=t/data=!4m20!1m13!4m12!1m3!2m2!1d107.1686063!2d-6.3232206!1m6!1m2!1s0x2e699b0c08ad8d01:0x2b18001d1b1371f9!2sUNIVERSITAS+PELITA+BANGSA,+Jl.+Inspeksi+Kalimalang+No.9,+Cibatu,+Cikarang+Sel.,+Kabupaten+Bekasi,+Jawa+Barat+17530!2m2!1d107.1692944!2d-6.3242459!3e9!3m5!1s0x2e699b0c08ad8d01:0x2b18001d1b1371f9!8m2!3d-6.3242459!4d107.1692944!16s%2Fg%2F1hm2jxhj1?entry=ttu"));
            startActivity(intent);
        });
```
### Output

![maps](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/b19e97ac-e3b8-44f3-a4d5-9b28019857db)

## 7. Telephon and kalender
```
code
```
```
buttonCalender.setOnClickListener(v -> {
            Intent intent = new Intent(Intent.ACTION_MAIN);
            intent.addCategory(Intent.CATEGORY_APP_CALENDAR);
            startActivity(intent);
        });
```
```
buttonTelpon.setOnClickListener(view -> {
            String numberDeveloper = "08+++++++";
            Intent intent = new Intent(Intent.ACTION_DIAL, Uri.parse("tel:" + numberDeveloper));
            startActivity(intent);
        });
```
### Output

![Screenshot_2024-01-17-13-21-17-941_com xiaomi calendar](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/81af72c7-429d-4890-9471-6e24253994f4)

![Screenshot_2024-01-17-13-21-31-711_app source getcontact](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/ba51efca-c73a-421b-ba9f-ce75bde37e60)

## 8. Fragment
```
code and design
```

![Screenshot (132)](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/610c4897-b195-4eb0-b7e3-053fe6912440)

### Output

![Screenshot_2024-01-17-13-22-20-704_com example RajaUAS](https://github.com/Rajahappyanto/Final_project_MobilePrograming-S3/assets/115520477/bfaf335b-d115-45e5-8b39-c4a391aff5c4)
