এটা ভুল syntax। CSS Grid-এ grid-column এভাবে লেখা যায় না।

সম্ভবত তুমি grid-template-columns এর কথা বলতে চাচ্ছো।repeat(2, 1fr) অর্থ:

2 = ২টি column তৈরি করবে।
1fr = প্রতিটি column সমান (equal) width নেবে।grid-column কী?

grid-column দিয়ে কোন item কোন column-এ থাকবে সেটা নির্ধারণ করা হয়।

উদাহরণ:

.item {
    grid-column: 1 / 3;
}