# Luxtory BD — Final

এই package-এর মূল website হলো `index.html`।

## Included
- ৫০টি বাংলা সাহিত্যকর্মের Library
- প্রতিটি বইয়ের embedded cover
- Luxtory BD-এর ভেতরের Reader
- Reader font controls + progress
- সাধারণ copy/select/right-click/print/save shortcut protection
- Author profile/photo
- 🇧🇩 বাংলাদেশের লেখক sector
- 🕌 আলাদা Islamic Library chamber
- Category + search
- নিজের লেখা submission form
- Supabase moderation/backend setup
- ZIP ছাড়া Owner Tools থেকে নতুন লেখা/বই যোগ করার foundation

## GitHub Pages
`index.html` এবং `CNAME` root-এ রাখুন। Site unpublish করবেন না।

## গুরুত্বপূর্ণ
Reader-এর public-domain বইগুলো উন্মুক্ত উৎস থেকে browser-এ Luxtory BD Reader-এর মধ্যে আনার চেষ্টা করে। কোনো উৎস সাময়িকভাবে পাঠ না দিলে Reader-এ error message দেখাবে; বাইরের source-এ স্বয়ংক্রিয়ভাবে পাঠককে পাঠানো হবে না।

Supabase চালু করলে submission ও admin moderation cross-device হবে। `supabase_setup.sql` ব্যবহার করে database/RLS সেটআপ করতে হবে। Browser-এ কখনো service_role/secret key দেবেন না।
