# TicTacToe 4x4 Game with React

โปรเจกต์เกม Tic-Tac-Toe ที่พัฒนาด้วย React มีการใช้งาน useState และ useEffect hooks เพื่อจัดการสถานะของเกม และรองรับการเล่นในขนาด 4x4.
**ทดลองเล่นได้ที่** 
[TicTacToe4x4 By Phakkapon ](https://tictactoe4x4byphakkapon.netlify.app/)
# ตัวอย่าง Game
![สกรีนช็อต 2024-06-27 164245](https://github.com/PhakkaponPumpour/TicTacToe-4x4/assets/134637954/646bdcdc-3926-4ebd-a2b1-0677af606d30)
## การติดตั้ง (Installation)

1.  **Clone โปรเจค**
	```bash
	git clone https://github.com/PhakkaponPumpour/TicTacToe-4x4.git
	```
2.  **จากนั้น cd ไปที่โปรเจคที่เราได้ Clone มา**
	```bash 
	cd TicTacToe-4x4
	```
3.	**ติดตั้ง dependencies:**
	```bash 
	npm install 
	```
4.  **เริ่มต้นการใช้งาน**
	```bash 
	npm start
	```
5.	 **เปิดเบราว์เซอร์และไปที่:**
		``` http://localhost:3000 ```


## โครงสร้างโปรเจกต์ (Project Structure)
 - **public/**: โฟลเดอร์ที่เก็บไฟล์สาธารณะ เช่น index.html 
 - **src/**: โฟลเดอร์ที่เก็บไฟล์ซอร์สโค้ดหลัก 
 - **components/**: โฟลเดอร์ที่เก็บคอมโพเนนต์ของ React 
	- **Board.jsx**
	- **GameHistorry.jsx** 		
	- **GameOver.jsx** 	
	- **GameState.js** 		
	- **Board.jsx** 		
	- **Reset.jsx**
	- **Strike.jsx** 		
	- **TicTacToe.jsx** 		
	- **Tile.jsx**
 - **App.js**: คอมโพเนนต์หลักของแอปพลิเคชัน 
 -  **index.js**: ไฟล์เริ่มต้นของแอปพลิเคชัน 
 - **App.css**: ไฟล์สไตล์ของแอปพลิเคชัน
## การออกแบบโปรแกรม (Application Design)
สร้าง Diagram ขึ้นมา เพื่อจัดการ Component ส่วนต่างๆทีต้องการจะใช้
![สกรีนช็อต 2024-06-27 164145](https://github.com/PhakkaponPumpour/TicTacToe-4x4/assets/134637954/1c0e943d-f79c-44df-8ebd-d68aa4dd4787)
