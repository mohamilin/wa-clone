This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More Documentation

welcome!
This documentation as learning process aboute Next.js, Typescript, Tailwind, Firebase. Enjoy & Happy `:-) :-) :-)`

1. Setup Project
    - we setup the project with command `npx create-next-app@latest` and choose some configuration :
        - √ What is your project named? ... whatsapp-clone
        - √ Would you like to use TypeScript? ... No / Yes  -> Y
        - √ Would you like to use ESLint? ... No / Yes  -> Y
        - √ Would you like to use Tailwind CSS? ... No / Yes -> Y
        - √ Would you like to use `src/` directory? ... No / Yes -> N
        - √ Would you like to use App Router? (recommended) ... No / Yes -> Y
        - √ Would you like to customize the default import alias? ... No / Yes -> Y
        - √ What import alias would you like configured? ... @/*
2. Happy Styling
    - Kita dapat menghapus semua className yang ada pada `page.tsx` karena kita akan membuat nya dari awal.
        * Styling on `page.tsx`   
            - dalam tag `main` kita berikan className `flex h-screen overflow-hidden`
                - `flex` agar element yang dibungkus dapat lebih lentur
                - `h-screen` agar dengan ketinggian yang ada jarak pandang tetap terjangkau 
                - `overflow-hidden` agar bisa memotong konten yang keluar dari element
            - Kemudian bwt `2` tag `div` di bawah `main` 
                - div pertama : kita akan bwt sidebar kiri untuk list chat yang telah dikirim oleh user-user
                    - Kita akan tambahkan className dengan :
                        - `bg-white-500` : background putih
                        - `w-1/3` : lebar 1/3 dari lebar total
                        - `overflow-y-auto` : agar selalu dapat di scroll secara vertical
                    - didalam tag ini kita akan berikan text : Sidebar Chat
                - div kedua : kita jadikan  sebagai space untuk menampilkan list user berdasarkan user yang dipilih.
                    - kita  tambahkan className :
                        - `w-full` agar lebar nya full 100%
                        - `overflow-y-auto`
                        - `flex` untuk menjalankan display flex
                        - `items-center`
                        - `justify-center`
                        - `bg-blue-50`
    * dsd
## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
