# OpenLay Feature Cards Rewrite

Tai lieu nay dung cho block 4 the trong section `Why OpenLay`.

Muc tieu:

- Lam 4 the ro nghia hon
- Giam trung lap y
- Tang kha nang doc nhanh
- Giup block nay noi ve `how we work`, khong lap lai section `Capabilities`

---

## Danh gia nhanh block hien tai

Van de chinh:

1. Copy dang qua generic
2. Card 1 va card 4 trung y mot phan
3. Icon card 1 va 4 qua giong nhau
4. Title chua deu luc
5. Card nhin sach nhung hoi rong va thieu diem nhan

Huong sua:

- Card 1: nhan vao nguyen tac lam viec
- Card 2: nhan vao model nhan su va ownership
- Card 3: nhan vao rollout / onboarding / handoff
- Card 4: nhan vao kha nang xay he thong noi bo

---

## Ban copy de xuat

### Card 1

**Title**

`Security-First Delivery`

**Description**

`Security requirements are considered from the start, so delivery stays stable, reviewable, and easier to operate later.`

**Y nghia**

Card nay noi ve cach OpenLay tiep can cong viec, khong phai chi noi "lam cybersecurity".

---

### Card 2

**Title**

`Dedicated Teams`

**Description**

`Focused engineering teams are matched to scope, timeline, and technical complexity, with clear ownership across delivery.`

**Y nghia**

Card nay giu lai duoc, chi can tighten copy de nghe chac hon.

---

### Card 3

**Title**

`Deployment and Onboarding`

**Description**

`We support rollout, integration, and onboarding so enterprise systems can move into real use without a messy handoff.`

**Y nghia**

Card nay can tach ro khoi card platform. Day la nang luc dua he thong vao van hanh.

---

### Card 4

**Title**

`Internal Platform Delivery`

**Description**

`We build and shape internal platforms and enterprise systems designed for long-term control, change, and operations.`

**Y nghia**

Card nay noi ro nang luc lam he thong noi bo, khong dung cum mo ho nhu `Platform Capability`.

---

## Ban copy ngan hon neu muon giu visual thoang

Neu muon ngan hon nua de card trong va sang hon:

### Card 1

**Title**

`Security-First Delivery`

**Description**

`Security is considered from day one, not added after delivery.`

### Card 2

**Title**

`Dedicated Teams`

**Description**

`Focused engineering teams with clear ownership across scope and delivery.`

### Card 3

**Title**

`Deployment and Onboarding`

**Description**

`Rollout and onboarding support for enterprise systems moving into real use.`

### Card 4

**Title**

`Internal Platform Delivery`

**Description**

`Internal systems built for long-term operation, control, and change.`

---

## Version toi khuyen dung

Neu uu tien can bang giua ro nghia va gon:

### Final copy

1. `Security-First Delivery`
   `Security requirements are considered from the start, so delivery stays stable and easier to operate later.`

2. `Dedicated Teams`
   `Focused engineering teams are matched to scope, timeline, and technical complexity, with clear ownership across delivery.`

3. `Deployment and Onboarding`
   `We support rollout, integration, and onboarding so enterprise systems can move into real use cleanly.`

4. `Internal Platform Delivery`
   `We build internal platforms and enterprise systems designed for long-term control, change, and operations.`

---

## Checklist xu ly

### P1 - Content

- [ ] Doi `Cybersecurity Focus` thanh `Security-First Delivery`
- [ ] Giu `Dedicated Teams`, nhung viet lai description
- [ ] Doi `Integration Support` thanh `Deployment and Onboarding`
- [ ] Doi `Platform Capability` thanh `Internal Platform Delivery`
- [ ] Dam bao 4 card khong lap lai y cua section `Capabilities`
- [ ] Dam bao moi card tra loi 1 cau hoi rieng:
  - [ ] OpenLay tiep can cong viec nhu the nao?
  - [ ] Team duoc to chuc ra sao?
  - [ ] Rollout va handoff duoc xu ly the nao?
  - [ ] OpenLay co the xay loai he thong nao?

### P1 - Design

- [ ] Doi icon card 4 sang icon khac ro rang voi card 1
- [ ] Kiem tra card 3 va 4 co icon khac nhau ve nghia
- [ ] Can nhac giam chieu cao card neu copy van ngan
- [ ] Neu giu chieu cao hien tai, them 1 detail nho de card bot rong:
  - [ ] keyword row, hoac
  - [ ] micro label, hoac
  - [ ] small supporting line
- [ ] Kiem tra line-length cua description, tranh qua dai tren desktop

### P1 - FE

- [ ] Update text content trong HTML
- [ ] Update icon cho card 4
- [ ] Kiem tra text wrap tren mobile
- [ ] Kiem tra card height dong deu khi xuong 1 cot
- [ ] Kiem tra hover state va border state dong deu

---

## Goi y neu muon tang chat cho block nay

Neu thay 4 card van hoi "mo", co the them 1 dong micro-label tren title.

Vi du:

- `Approach` -> `Security-First Delivery`
- `Team Model` -> `Dedicated Teams`
- `Rollout` -> `Deployment and Onboarding`
- `Build Scope` -> `Internal Platform Delivery`

Chi nen dung neu muon tang kha nang scan. Khong bat buoc.

---

## Dieu can tranh

- Khong dung lai `Platform Capability`
- Khong dung lai icon qua giong nhau
- Khong de card 1 noi lai y "chung toi lam security"
- Khong de card 3 va 4 cung noi chung ve "enterprise systems" ma khong tach vai tro
- Khong viet description bang nhung cum tu slogan rong

---

## Definition of done

Chi xem la xong khi:

- [ ] User doc 4 the va hieu moi the noi mot y khac nhau
- [ ] Card 1 khong con generic
- [ ] Card 4 khong con abstract
- [ ] Icon card 1 va 4 khong con gay nham
- [ ] Block nay bo sung cho `Capabilities`, khong lap lai no
