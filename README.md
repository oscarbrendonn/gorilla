# Gorilla

67 gorilla karakteri. Tripo uretimi, doku onarimi yapilmis son surum.

Dosyalar:

- gorilla.glb - SON VERSIYON. Rigli (19 kemik, oyunda kullanima hazir), doku onarimli. 373k ucgen, 4096 doku (PNG).
- gorilla_static.glb - Ayni model rigsiz (statik biblo hali).
- gorilla_tpose.glb - T-pozda (kollar yatay). En iyi surum (v12); bilek/koltukalti eski temas hattinda kucuk izler kalir - kaynasik cok-kabuklu kaynak geometrinin yapisal siniri.
- gorilla_apose.glb - A-pozda (kollar 45 derece). Ayni sinirlar gecerli.
- gorilla_parts_rig.glb - 67VERSE PARCALI RIG: Tripo segmentation ile 14 parca + friendsies master iskeleti (20 kemik, AttachmentL/R + Backpiece_Attachment). Yuruyuste kirilma yok.
- Canli 3D goruntuleyici: https://oscarbrendonn.github.io/gorilla/

Notlar:

- Orijinal Tripo ciktisindaki boya kirilmalari (cene yanlari, dikis cizgileri) sadece doku duzeyinde onarildi; geometri orijinalle ayni.
- Iskelet: root, hips, spine, chest, head + kol (shoulder/upper_arm/forearm/hand) ve bacak (thigh/shin/foot) L/R.
- Pozisyonlar float32 (three.js r128 raycast uyumlu).
