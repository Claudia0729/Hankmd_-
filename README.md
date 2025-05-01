# **何謂MVC與MVVM**
<div style="text-align: justify;">
若想讓一個程式有畫面、有控制、有運算時，必須要設計有關APP畫面上的元件，也必須要撰寫有關程式邏輯的，ex:計算或什麼樣的資料是是合理的等。同時也需要控制流程，若按下某個動作要到另一個畫面等地程式碼。-> 所有東西都使用程式碼撰寫，那就會造成很大的困擾。Ex:針對畫面的微調，仍需要程式設計師到場。</div>
<div style="text-align: center;">
  <img src="https://hackmd.io/_uploads/SJLOdxVRyg.png" alt="未分類前的MVC" style="width:60%;">
</div>

<div style="text-align: justify;">
Android是由Google所設計的開發架構，因此就分為MVC三個。</div>
<div style="text-align: center;">
  <img src="https://hackmd.io/_uploads/S1qh3lVR1x.png" alt="MVC的分類筆記" style="width:75%;">
</div>

<div style="text-align: justify;">
但是Controller( Activity) 程式裡面，常常需要去呼叫Mode(Class)紅色部分，因此也會有他的程式碼部分。若畫面需要做改變，ex:大小/蹦出對話框等地，程式碼也必須寫進Controller裡面。因此當畫面更豐富、更複雜，那Controller內的程式碼就會越變越多。-> MVC經常遇到的設計上的問題。
</div>
<div style="text-align: center;">
  <img src="https://hackmd.io/_uploads/BygO-3gell.png" alt="MVC的分類筆記" style="width:25%;">
</div>

<div style="text-align: justify;">
MVVM的誕生: 原本的MV + 後來的ViewModel(VM)。 
</div>
<div style="text-align: center;">
  <img src="https://hackmd.io/_uploads/ry2XQ2eglg.png" alt="MVC的分類筆記" style="width:70%;">
</div>











