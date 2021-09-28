
# TV System Debugging Tools By Thai-Dev

แอพ Android เทอร์มินัล / คอนโซลเชิงบรรทัดสำหรับอุปกรณ์ที่มีอินเตอร์เฟสซีเรียล / UART ที่เชื่อมต่อกับตัวแปลง USB เป็นซีเรียล

## รองรับ USB เป็นตัวแปลงอนุกรม

-RT809x Mstar Debug TV-
-FTDI FT232, FT2232, ...
-Prolific PL2303
-Silabs CP2102, CP2105, ...
-Qinheng CH340, CH341

และอุปกรณ์ที่ใช้โปรโตคอล USB CDC เช่น

- Arduino โดยใช้ ATmega32U4
- Digispark โดยใช้ V-USB ซอฟต์แวร์ USB
- BBC micro:bit โดยใช้ ARM mbed เฟิร์มแวร์ DAPLink

## คุณสมบัติ

- การจัดการสิทธิ์ในการเชื่อมต่ออุปกรณ์
- บริการเบื้องหน้าเพื่อบัฟเฟอร์รับข้อมูลในขณะที่แอปกำลังหมุนอยู่ในพื้นหลัง ...

### Build สถานะ   

| ติดตาม | สถานะ                                                                                                                                                                                                                                                        |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Production | [![Build status](https://build.appcenter.ms/v0.1/apps/1e1a1b27-79f7-4a73-bc71-4fb8788f314e/branches/production/badge)](https://appcenter.ms) |
| Beta | [![Build status](https://build.appcenter.ms/v0.1/apps/1e1a1b27-79f7-4a73-bc71-4fb8788f314e/branches/beta/badge)](https://appcenter.ms) |
| Alpha | [![Build status](https://build.appcenter.ms/v0.1/apps/1e1a1b27-79f7-4a73-bc71-4fb8788f314e/branches/alpha/badge)](https://appcenter.ms) |

## เครดิต

แอปนี้ใช้ไลบรารี [usb-serial-for-android](https://github.com/mik3y/usb-serial-for-android)

แอปนี้ใช้แอป [SimpleUsbTerminal] (https://github.com/kai-morich/SimpleUsbTerminal)

