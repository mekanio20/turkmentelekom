# Daşoguztelekom Işgärler Sistemi

Bu proýekt Daşoguztelekom kärhanasynyň işgärleriniň sanawyny dolandyrmak üçin ýaratylan web ulgamy.

## Özellikler

- Işgärleriň sanawyny görüntülemek
- Täze işgär hasaba almak
- Işgär maglumatlaryny üýtgetmek
- Işgär pozmak
- Işgärleri bölüm we wezîpe boýunça süzgüçlemek
- Işgärleri ady boýunça gözlemek

## Teknik Gereksinimler

- Node.js (v14 ýa-da ýokary)
- PostgreSQL (v12 ýa-da ýokary)

## Gurnamak

1. Proýekti klonlaň:
```bash
git clone https://github.com/yourusername/dashoguztelekom.git
cd dashoguztelekom
```

2. Backend bağlylyklaryny gurnaň:
```bash
cd backend
npm install
```

3. Frontend bağlylyklaryny gurnaň:
```bash
cd frontend
npm install
```

4. PostgreSQL bazasyny gurnaň we `.env` faylini düzenleň:
```env
DB_HOST=localhost
DB_PORT=5432
DB_NAME=dashoguztelekom
DB_USER=your_username
DB_PASSWORD=your_password
```

5. Backend serwerini işe tüşüriň:
```bash
cd backend
npm run dev
```

6. Frontend serwerini işe tüşüriň:
```bash
cd frontend
npm run dev
```

## Ulanyş

1. Brauzeriňizde `http://localhost:3000` salgysyna giriň
2. Işgärler sanawyny görüntülemek üçin "Işgärler" bölümine geçiň
3. Täze işgär hasaba almak üçin "Täze Işgär" düwmesine basyň
4. Işgär maglumatlaryny üýtgetmek üçin "Üýtgetmek" düwmesine basyň
5. Işgär pozmak üçin "Pozmak" düwmesine basyň

## Teknologiýalar

- Frontend:
  - Vue.js 3
  - Tailwind CSS
  - Axios

- Backend:
  - Node.js
  - Express.js
  - Sequelize ORM
  - PostgreSQL

## Lisensiýa

Bu proýekt MIT lisenziýasy astynda ýaybaşlanýar. Giňişleýin maglumat üçin `LICENSE` faylyna serediň. 