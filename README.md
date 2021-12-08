Belajar delfi 7
// cara buat program awal

Var 
  nama : string;
  umur : interger;
  tinggibadan : real;
  beratbadan : real;
  anakke : interger;
  saudara : interger;
  a : string
  nilai : double;
  uas : double;
  uts : double;
  tugas : double;
  
  // Input 
write('Masukkan nama: '); readln(nama);
write('Masukkan umur: '); readln(umur);
write('Masukkan tinggi badan: '); readln(tinggibadan);
write('Masukkan berat badan: '); readln(beratbadan);
write('Anak ke: '); readln(anakke);
write('banyak saudara: '); readln(saudara); 

  //Output
writeln('Nama yang diinputkan adalah: ', nama);
writeln('Umur yang diinputkan adalah: ', umur);
writeln('Tinggi badan yang diinputkan adalah: ', tinggibadan);
writeln('berat badan yang diinputkan adalah: ', beratbadan);
writeln('anak ke ', anakke, ' dari 'saudara, ' saudara');

  //Input nilai
  write('masukkan nilai: ');
  readln(nilai);
  
  //Output
 IF nilai > 80 then
  writeln('Lulus');
 else
  writenld('gagal');

 readln;
 

readln(banyak);

Var
  Nama : [0..100] of string;
  Nilai : [0..100] of integer;
  Banyak : integer;

  for i:=0 to banyak-1 do
  begin
        readln(nama[i]);
        readln(nilai[i]);
  end;


  // --------------------------------------------
  writeln('siswa yang lulus:');
  for i:=0 to banyak-1 do
  begin
      if nilai[i] > 70 then
      begin
          writeln(nama[i], ' ', nilai[i]);
      end;
  end;

  writeln('siswa yang gagal:');
  for i:=0 to banyak-1 do
  begin
      if nilai[i] <= 70 then
      begin
          writeln(nama[i], ' ', nilai[i]);
      end;
  end;

  readln;
 


Var
Var
  Nama : [0..100] of string;
  Nilai : [0..100] of integer;
  Banyak : integer;

  for i:=0 to banyak-1 do
  begin
        readln(nama[i]);
        readln(nilai[i]);
  end;


  // --------------------------------------------
  writeln('siswa yang dapat nilai C:');
  for i:=0 to banyak-1 do
  begin
      if nilai[i] < 70 then
      begin
          writeln(nama[i], ' ', nilai[i]);
      end;
  end;

  writeln('siswa yang nilai B:');
  for i:=0 to banyak-1 do
  begin
     Else 
      if nilai[i] > 80 then
      begin
          writeln(nama[i], ' ', nilai[i]);
      end;
  end;


 writeln('siswa yang nilai A:');
  for i:=0 to banyak-1 do
  begin
     Else
      begin
          writeln(nama[i], ' ', nilai[i]);
      end;
  end;

  readln;
