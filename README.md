#### Saya Ihsan Ghozi Zulfikar NIM 2103303 mengerjakan soal TP 1 dalam mata kuliah DPBO untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin

### Kelas: Human
* terdiri dari name dan gender

### Kelas: StudentGrade
* terdiri dari studentName, courseName, professorGrade, dan assistantGrade

### Kelas CollegeStudent
* inherit kelas Human, karena mahasiswa adalah manusia
* terdiri dari nim, textbook, laptop dan studentGradeList
* studentGradeList adalah list dari objek StudentGrade

### Kelas Course
* terdiri dari courseId, courseName, dan studentList
* studentList adalah list dari objek CollegeStudent

### Kelas Instructor
* terdiri dari courseList
* courseList adalah list dari objek Course

### Kelas Professor
* inherit kelas Human karena dosen adalah manusia
* inherit kelas Instructor karena dosen adalah instruktur
* terdiri dari nip, whiteboardMarker, dan laptop

### Kelas AssistantStudent
* inherit kelas CollegeStudent karena asisten adalah mahasiswa
* inherit kelas Instructor karena dosen adalah instruktur

### Kelas Bem
* terdiri dari plannedProgram, implementedProgram, dan accomplishedPrograms
* accomplishedProgram adalah list dari string 

### Kelas BemStudent
* inherit kelas CollegeStudent karena anggota bem adalah mahasiswa
* terdiri dari bem
* bem adalah objek Bem

### Kelas Ec
* terdiri dari ecPrograms
* ecPrograms adalah list dari string

### Kelas EcStudent
* terdiri dari ec dan languageSkill
* ec adalah objek Ec


## Dokumentasi
![tp1_uml](https://user-images.githubusercontent.com/100748074/224967106-915a5ce1-4893-4fd2-8ce6-912c6d217467.png)

