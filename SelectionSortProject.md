<h2>Proje</h2>
<strong>[22,27,16,2,18,6] -> Insertion Sort</strong>

<strong>1 = Yukarı verilen dizinin sort türüne göre aşamalarını yazınız</strong>

<strong>2 = Big-O gösterimini yazınız</strong>

<strong>3 = Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız</strong>
<ul>
  <li>Average case: Aradığımız sayının ortada olması</li>
  <li>Worst case: Aradığımız sayının sonda olması</li>
  <li>Best case: Aradığımız sayının dizinin en başında olması.</li>
</ul>
<strong>4 = [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.</strong>

<h2>Cevap</h2>
<strong>1 =</strong>
<ul>
  <li>[2,27,16,22,18,6] -> 2 dizinin küçük sayısıdır, en başa alabilmek için 22 ile yer değiştirir.</li>
  <li>[2,6,16,22,18,27] -> İkinci küçük sayı 6'dır ikinci sıraya almak için 27 ile yer değiştirir.</li>
  <li>[2,6,16,18,22,27] -> Üçüncü sayı 16'dır, sıralaması doğru olduğu için herhangi bir değişiklik yapılmaz. Dördüncü sayı 18'dir ve sıralamaya uygun olması için 22 ile yer değiştirir.</li>
  <li>Beşinci ve altıncı sayı sıralamaya uygun olduğundan sıralamada herhangi bir değişiklik yapılmaz.</li>
</ul>
<strong>2 =</strong>
<ul>
  <li>22,27,16,2,18,6] dizisinde 6 tane eleman vardır, yani 6 tane işlem yapılacaktır demektir.</li>
  <li>ilk adımda n-> 6 tane işlem,</li>
  <li>ikinci adımda en küçük elemanı (yani birinci) bulmak için (n-1)-> 6-1=5 tane işlem,</li>
  <li>Üçüncü adımda ikinci elemanı bulmak için (n-2)-> 6-2=4 tane işlem,</li>
  <li>Dördüncü adımda üçüncü elemanı bulmak için (n-3)-> 6-3=3 tane işlem,</li>
  <li>Beşinci adımda dördüncü elemanı bulmak için (n-4)-> 6-4=2 tane işlem yapılır.</li>
  <li>Altı elemanlı dizi olduğu için daha fazla işlem yapılmasına gerek yoktur çünkü son eleman altıncı elemandır.</li>
</ul>
<p>Bu algoritmada n+(n-1)+(n-2)+(n-3)+(n-4)+1 kadar işlem yapılır. Bu işlemin formülü: [n(n+1)]/2'dir. Bu formül sadeleştirilerek: <strong>(n²+n)/2</strong> elde edilir.</p>
<p>Big-O Notation'da kat sayı önemsizdir; yani domine eden fonksiyon<strong> n² </strong>alınır.</p>
<p><strong>Big-O değeri = O(n²)</strong></p>
<strong>3 = Aradığımız sayı 18 dizinin ortasında olduğu için bu avarage case kapsamına girer.</strong>
<p><strong>4 =</strong><p> 
<ol>
  <li>[2|3,5,8,7,9,4,15,6]</li>
  <li>[2,3|5,8,7,9,4,15,6] 3</li>
  <li>[2,3,4|7,9,5,15,6] 4</li>
  <li>[2,3,4,5,7,9,8,15,6]</li>
</ol>
