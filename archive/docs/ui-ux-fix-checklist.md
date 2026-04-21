# OpenLay UI/UX Fix Checklist

Checklist nay duoc viet cho trang `https://openlay.pages.dev` theo muc tieu: ro hon, thuyet phuc hon, de maintain hon, nhung khong dua vao trust signal nhu case study hay logo khach hang.

## Cach dung checklist

- Lam theo thu tu tu `P1` den `P3`.
- Moi muc co:
  - `Muc tieu`
  - `Can sua`
  - `Output can co`
  - `Owner goi y`
- Khong can sua tung chi tiet mot luc. Nen chot `P1` truoc, test lai, roi moi sang `P2`.

---

## P1 - Sua de dung huong ngay

### 1. Chot lai thong diep dinh vi trong hero

**Muc tieu**

Lam ro OpenLay la ai, ban gi, va phu hop voi ai trong 3-5 giay dau.

**Can sua**

- Xem lai `h1` hien tai: `Security engineering for enterprise systems.`
- Xem lai subheadline hien tai: `We build, secure, and operate enterprise platforms - end to end.`
- Rut gon va cu the hon:
  - OpenLay lam gi?
  - Doi tuong nao phu hop?
  - 3 nhom nang luc lien ket voi nhau ra sao?

**Yeu cau**

- Headline khong chi "nghe hay", ma phai mo ta duoc offer.
- Subheadline khong lap lai y cua headline.
- Tranh tu qua chung chung: `enterprise`, `platform`, `delivery`, `secure` neu dung lien tiep ma khong them thong tin moi.

**Output can co**

- 3 phuong an `h1 + subheadline`
- Chon 1 phuong an de dua vao code

**Owner goi y**

- Content
- Founder
- Design review

---

### 2. Bo CTA `Schedule a Call` va thiet ke lai hanh vi chinh

**Muc tieu**

Giam cam giac ep user phai book call ngay khi trust con thap.

**Can sua**

- Xoa `Schedule a Call` o nav
- Xoa `Schedule a Call` o hero neu van giu nguy van ban hien tai
- Chon 1 trong 2 huong:

**Huong A - Van giu CTA mem**

- Nav CTA: `Contact`
- Hero primary CTA: `Discuss Your Project`
- Hero secondary CTA: `View Capabilities`

**Huong B - Khong giu CTA noi bat o nav**

- Nav chi de link section
- Hero chi giu 1 CTA mem

**Yeu cau**

- Khong de 1 card co CTA, 2 card con lai khong co, neu chua co ly do ro rang.
- Moi CTA phai dan den hanh dong hop logic voi stage cua user.

**Output can co**

- 1 phuong an CTA cho nav
- 1 phuong an CTA cho hero
- Mapping ro: click vao thi user di dau

**Owner goi y**

- Content
- Design
- FE

---

### 3. Viet lai section `Capabilities` de tach ro 3 nhom dich vu

**Muc tieu**

De user doc 10-15 giay la hieu ro khac nhau giua:

- Cybersecurity Services
- Outsourcing Teams
- Security Platform Delivery

**Can sua**

- Xem lai title section: `Security, Outsourcing, Platform Delivery`
- Xem lai section desc: `Three capabilities, one delivery team.`
- Viet lai copy moi card theo format thong nhat:
  - Van de / nhu cau
  - OpenLay cung cap gi
  - Dau ra / ket qua user nhan duoc

**Checklist chi tiet**

- [ ] Card 1 noi ro pham vi cybersecurity
- [ ] Card 2 noi ro outsourcing la model van hanh, khong phai "ban nguoi" mo ho
- [ ] Card 3 noi ro platform delivery la xay dung / tich hop / van hanh he thong nao
- [ ] Moi card co 1 cau mo ta khac nhau that su
- [ ] Neu co CTA, tat ca card deu nhat quan

**Output can co**

- 1 heading moi cho section
- 1 subheading moi
- 3 doan copy moi cho 3 card

**Owner goi y**

- Content
- Founder
- FE update

---

### 4. Sua `Why OpenLay` de thanh section ve "cach lam", khong lap lai services

**Muc tieu**

Bien section nay thanh ly do de tiep tuc quan tam, thay vi lap lai y "chung toi lam security / platform".

**Can sua**

- Kiem tra tung card trong section `Why OpenLay`
- Loai bo nhung y trung voi section `Capabilities`
- Chuyen trong tam sang:
  - Cach tiep can
  - Cach trien khai
  - Cach ban giao
  - Cach dong hanh sau rollout

**Format goi y**

- `How we work`
- `What we own`
- `How we deliver`
- `What happens after launch`

**Checklist chi tiet**

- [ ] Spotlight card noi ro quy trinh lam viec
- [ ] Cac card phu khong lap lai ten dich vu
- [ ] Moi card tra loi 1 cau hoi cu the cua user
- [ ] Copy ngan hon, biet "noi cai gi" va "khong noi cai gi"

**Output can co**

- 1 title moi cho section
- 1 section desc moi
- 1 spotlight copy moi
- 4 card con lai viet lai hoan toan

**Owner goi y**

- Content
- Design

---

### 5. Sap xep lai flow noi dung tren trang

**Muc tieu**

Moi section co vai tro ro rang, khong lap y.

**Flow goi y**

1. Hero: OpenLay la ai
2. Capabilities: OpenLay lam gi
3. Working model / Why OpenLay: OpenLay lam nhu the nao
4. Contact: buoc tiep theo la gi
5. Legal: dua xuong footer hoac trang rieng

**Checklist chi tiet**

- [ ] Proof strip co con can ton tai khong?
- [ ] Neu giu proof strip, noi dung phai bo sung thong tin moi
- [ ] Khong de 2 section lien nhau noi cung 1 y bang 2 cach
- [ ] Contact phai xuat hien truoc legal

**Output can co**

- 1 wireframe flow text-only cho landing page

**Owner goi y**

- Design
- Content
- FE

---

## P2 - Sua de tang kha nang chuyen doi va chat luong doc

### 6. Viet lai copy theo huong it slogan, nhieu thong tin hon

**Muc tieu**

Lam copy it "marketing chung chung" hon va thuc dung hon.

**Can sua**

- Ra soat toan bo copy trong:
  - Hero
  - Proof strip
  - Services
  - Why OpenLay
  - Contact

**Nguyen tac**

- Moi cau phai them thong tin moi
- Neu 2 cau co the doi cho nhau ma khong anh huong nghia, nghia la dang qua generic
- Uu tien danh tu va dong tu cu the

**Checklist chi tiet**

- [ ] Bo bot cum tu lap lai
- [ ] Tranh dung lien tiep `secure`, `enterprise`, `platform`, `delivery`
- [ ] Moi section co 1 thong diep chinh duy nhat
- [ ] Subheadline ngan, de doc tren mobile

**Output can co**

- Ban copy clean cho toan bo page

**Owner goi y**

- Content

---

### 7. Sua contact section de user biet phai lam gi tiep

**Muc tieu**

Khong chi "cho thong tin lien he", ma huong dan user cach lien he hop ly.

**Can sua**

- Them 1 doan ngan giai thich:
  - Khi nao nen lien he
  - OpenLay se phan hoi nhu the nao
  - User nen gui gi trong email

**Checklist chi tiet**

- [ ] Co 1 opening line ro rang
- [ ] Khong chi liet ke email / phone / address
- [ ] Neu khong co form, email link phai la hanh dong chinh
- [ ] Noi dung contact gon, khong trang tri qua muc

**Output can co**

- 1 contact intro moi
- 1 primary contact path ro rang

**Owner goi y**

- Content
- FE

---

### 8. Rut legal ra khoi luong chinh cua landing page

**Muc tieu**

Khong de legal lam dut mach doc va giam conversion.

**Can sua**

- Dua `Privacy Policy` va `Terms of Use` sang:
  - trang rieng, hoac
  - modal / page rieng, hoac
  - footer link

**Checklist chi tiet**

- [ ] Hero -> services -> why -> contact ket thuc gon
- [ ] Legal khong chiem mot section lon tren landing page
- [ ] Footer van co link legal day du

**Output can co**

- 2 file legal rieng, hoac placeholder route rieng

**Owner goi y**

- FE
- Founder review

---

### 9. Dong bo hanh vi tuong tac tren cac card

**Muc tieu**

Khong de UI tao cam giac "dang dang do".

**Can sua**

- Hien tai chi co card `Cybersecurity Services` co link `Talk to us`
- Chon 1 trong 3 huong:
  - Tat ca card deu co CTA
  - Tat ca card deu khong co CTA
  - Card nao co CTA thi card do phai duoc giai thich vi sao la offer chinh

**Checklist chi tiet**

- [ ] Hover states dong deu
- [ ] Link styles dong deu
- [ ] Card featured co ly do ro rang
- [ ] Badge text co nghia that, khong chi de trang tri

**Output can co**

- Rule thong nhat cho tat ca product/service cards

**Owner goi y**

- Design
- FE

---

### 10. Chinh lai nhan dien visual de bot cam giac template

**Muc tieu**

Tao cho trang mot net rieng hon ma khong can lam phuc tap.

**Can sua**

- Ra soat:
  - accent color
  - icon style
  - illustration style
  - typography hierarchy
  - tone cua headline

**Checklist chi tiet**

- [ ] Chon 1 visual motif xuyen suot
- [ ] Giam cam giac "SaaS template" o hero va cards
- [ ] Dung cung 1 ngon ngu hinh anh cho tat ca illustrations
- [ ] Kiem tra palette co qua generic khong

**Output can co**

- Mini style direction 1 trang

**Owner goi y**

- Design

---

## P3 - Sua de site ben hon, de maintain hon

### 11. Tach asset image ra khoi HTML inline

**Muc tieu**

Giam kich thuoc HTML, tang kha nang cache, de maintain.

**Can sua**

- Khong inline base64 image trong HTML
- Dung file asset rieng trong thu muc `images/`

**Checklist chi tiet**

- [ ] Hero image goi tu file asset
- [ ] Service images goi tu file asset
- [ ] Logo khong embed base64 trong source
- [ ] Test lai duong dan asset sau khi build/deploy

**Output can co**

- HTML sach hon
- Asset loading hop ly hon

**Owner goi y**

- FE

---

### 12. Tach CSS ra file rieng neu site con phat trien tiep

**Muc tieu**

De sua, review, versioning va maintain de hon.

**Can sua**

- Dua CSS inline sang file rieng, vi du:
  - `styles/main.css`

**Checklist chi tiet**

- [ ] Khong pha vo current design
- [ ] Tiep tuc giu token va structure ro rang
- [ ] Co chia section CSS hop ly

**Output can co**

- 1 CSS file sach, co comment section

**Owner goi y**

- FE

---

### 13. Them tracking co ban cho landing page

**Muc tieu**

Biet user click vao dau, section nao co gia tri, CTA nao co tac dung.

**Can sua**

- Theo doi:
  - click nav
  - click CTA hero
  - click mailto
  - click tel
  - scroll depth

**Checklist chi tiet**

- [ ] Co event name ro rang
- [ ] Co quy uoc dat ten
- [ ] Khong spam tracking vo nghia

**Output can co**

- 1 tracking plan ngan

**Owner goi y**

- FE
- Founder

---

### 14. Rà soat accessibility thuc te

**Muc tieu**

Trang de dung hon tren mobile, keyboard, va trong dieu kien thuc te.

**Can sua**

- Test keyboard nav
- Test focus states
- Test contrast
- Test mobile nav
- Test text wrap tren man hinh hep

**Checklist chi tiet**

- [ ] Menu mobile dong/mo on dinh
- [ ] Button va link co focus state ro
- [ ] Khong co text qua sat background
- [ ] Khong co noi dung bi tran / vo layout o mobile

**Output can co**

- 1 bug list accessibility neu co

**Owner goi y**

- FE
- QA

---

## Thu tu thuc hien de nghi

### Sprint 1

- [ ] Sua hero
- [ ] Bo / thay CTA `Schedule a Call`
- [ ] Viet lai `Capabilities`
- [ ] Viet lai `Why OpenLay`
- [ ] Sap xep lai flow tong the

### Sprint 2

- [ ] Toi uu copy toan trang
- [ ] Sua contact section
- [ ] Dua legal xuong footer / trang rieng
- [ ] Dong bo cards va interaction
- [ ] Chot visual direction

### Sprint 3

- [ ] Tach asset khoi HTML
- [ ] Tach CSS
- [ ] Them analytics
- [ ] Test accessibility va mobile

---

## Definition of done

Chi xem la xong khi dat du cac diem sau:

- [ ] User vao trang va hieu OpenLay lam gi trong 5 giay dau
- [ ] Khong con `Schedule a Call`
- [ ] 3 nhom dich vu khac nhau ro rang
- [ ] `Why OpenLay` khong lap lai `Capabilities`
- [ ] Contact section cho user biet buoc tiep theo
- [ ] Legal khong con pha mach landing page
- [ ] Source HTML khong con image base64 lon
- [ ] Site doc tot tren mobile

---

## Ghi chu cho luc implementation

- Neu chua chot duoc brand voice, uu tien copy ro rang truoc khi "hay".
- Neu chua muon lam form, email van du, nhung phai duoc dat vao dung context.
- Neu chua co trust signal, cang phai lam ro offer, scope va cach lam viec.
- Khong nen sua visual truoc khi chot lai noi dung va flow.
