# CA_Final

## - 1. Topic
**消失的學分(Gone Credits)**

## - 2. Motivation
國立交通大學與國立陽明大學於2021年2月1日合併為國立陽明交通大學，我們以併校為主題發想，做出一部有趣的3D動畫短片，敘述併校後第一屆畢業生的甘苦談。

## - 3. Outline
小宏是一名交大大四的學生，有一天，他拿著一袋學分要去自動販賣機列印畢業證書，但正當他要將學分投入販賣機時，突然停電了，而當燈再次亮起時，小宏手上的學分已經消失無蹤，取而代之的一張紙條，上面寫著「想拿回學分就到陽明大學吧！」，於上小宏踏上前往陽明大學找回學分之旅。

## - 4. Tool
* **Unity** : 遊戲引擎，方便搭建影片中的場景、鏡頭控制、畫面後處理。  

* **Umotion** : Unity中的第三方動畫編輯套件，可以進行基本的keyframe編輯。  

* **VRoid Studio** : 用來製作和編輯動畫角色，輸出出來的角色模型自帶表情，且匯入到Unity中還會添加dynamic bone腳本，以此來產生頭髮、領帶、裙子擺動的物理效果。

## - 5. Implement
**1. 建立場景**：除了少數幾個比較特殊的模型(學分金幣、校門口等等)之外，大部分使用的都是 Unity Asset Store 上面的免費素材，我們用這些素材建立了一共五個場景：交大工三走廊、陽明大學校門口、校長室、操場、從交大到陽明的路程。  

**2. 角色模型**：故事中的三位角色(交大學生小宏、陽明大學手下、陽明大學校長)都是使用 VRoid Studio 建立出來的。  

**3. 角色動畫**：我們使用 Unity Asset Store 上的套件 Umotion 進行角色動畫的編輯，它除了可以記錄角色的動作在特定的 frame 上之外，還有 Muscle Groups 的功能，可以一次調整多個關節，例如一次調整四根手指的屈伸，它還可以在 Unity 處於 Play Mode 的時候進行動畫的編輯，也可以與 Unity 的 Timeline 進行同步的播放。編輯完動作之後即可匯出成 anim 檔案供角色使用。  

**4. 轉場動畫**：我們使用一塊佔滿整個螢幕的色塊，並在它身上新增一個透明度會隨著時間改變的動畫來達成淡入淡出的轉場動畫。  

**5. 音效**：我們使用的背景音樂、音效素材來源包含 Unity Asset Store、Youtube、[效果音ラボ](https://soundeffect-lab.info/ "link")  

**6. 時間軸控制**：我們把編輯好的角色動畫、鏡頭動畫、場景物件動畫以及音效等等匯入到 Unity 的 Timeline 裡面，並調整適當的時間點。  
 
**7. 影片後製**：我們使用 Premiere Pro 進行影片的後製，包含把各場景的動畫串再一起、加上背景音樂並調整聲音的平衡、上字幕等等。

## - 6. Image Show
![image](https://drive.google.com/uc?export=view&id=1WNm6oSDHPO6IDxHCBsoPDi5MeYbpsiGl)
![image](https://drive.google.com/uc?export=view&id=1te6eqLsOFNpvHc_tgOVYFY2QKvPZId73)
![image](https://drive.google.com/uc?export=view&id=1AUTNUlAAEkSOLZgRDsr2V6HOy4zgdkWm)
![image](https://drive.google.com/uc?export=view&id=1rR3tmop2f6pNkT4DXUz3VLB2DAuXpBxw)
## - 7. Demo Video
[![Watch the video](https://drive.google.com/uc?export=view&id=1KOgZhUwef6RcXuOnoVi3ctT-nxMpWQKg)](https://www.youtube.com/watch?v=7PEAWuVoJho&list=UUA709PCPAKldQfmaCe1aj3w&index=4)

## - 8. Work division
陳君杰：人物動作、鏡頭位置、配音  
邱兆國：素材蒐集、場景建構、配音  
謝至恆：人物動作、影片後製、配音  

