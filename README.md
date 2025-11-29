1. สร้างตารางชื่อ production และสร้างตารางใน Schema ชื่อ raw_data  ของ PostgreSQL 
2. ใช้โค้ด ingest.py เพื่อโหลด DataFrame ลง
3. ใช้โค้ด transform.py อ่านข้อมูลในตาราง raw_data แล้วจะทำการ Cleaning, Transformation, Aggregation
4. ใช้โค้ด publish.py เพื่อเขียน DataFrame ลงไปยัง Google Sheets โดยผ่าน google cloud api
