<h2>Proje</h2>
<p><strong>[16,21,11,8,12,22] -> Merge Sort</strong></p>
<ul>
  <li>Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.</li>
  <li>Big-O gösterimini yazınız.</li>
</ul>
<h2>Cevap</h2>
<h4>Önce parçalama işlemini yapıyoruz!</h4>
<p><strong>1 -></strong> [16,21,11,8,12,22]</p>
<p><strong>2 -></strong> [16,21,11] [8,12,22]</p>
<p><strong>3 -></strong> [16,21] [11] [8,12] [22]</p>
<p><strong>4 -></strong> [16] [21] [11] [8] [12] [22]</p>
<h4>Şimdi de birleştiriyoruz!</h4>
<p><strong>5 -></strong> [16,21] [8,11] [12,22]</p>
<p><strong>6 -></strong> [8,11,16,21] [12,22]</p>
<p><strong>7 -></strong> [8,11,12,16,21,22]</p>
<p>Böylelikle <strong>7</strong> işlemde sıralamış olduk!</p>

<img src="mergesort.png">
