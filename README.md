# SELabEXP2
| نام          | شماره دانشجویی|
| ------------- | ------------- |
| علیرضا عالیپناه                  | 99106396      |
| سیدمحمدیوسف نجفی      | 99102361      |
| علی نظری                        | 99102401      |


جدول خواسته شده برای آزمایش اول به شرح زیر پر می‌شود:

<table dir='rtl'>
<tbody>

<tr>
<td width="64">
<p><strong>ردیف</strong></p>
</td>
<td width="198">
<p><strong>محل اعمال تغییرات (کلاس/واسط)</strong></p>
</td>
<td width="141">
<p><strong>عنوان تغییر</strong></p>
</td>
<td width="292">
<p><strong>شرحی کوتاه از تغییر</strong></p>
</td>
</tr>

<tr>
<td width="64">
<p><strong>۱</strong></p>
</td>
<td width="198">
<p>PhoneOrderService</p>
</td>
<td width="141">
<p>افزودن کلاس جدید برای سفارش های از طریق موبایل</p>
</td>
<td width="292">
<p>در این کلاس که از واسط OrderService استفاده می کند، ۶ تابع موجود است که ۴ تای آن دارای بدنه خالی است و دو مورد از آن دارای پیاده سازی است که مربوط به ثبت سفارش و پرداخت از طریق موبایل است.</p>
</td>
</tr>

<tr>
<td width="64">
<p><strong>۲</strong></p>
</td>
<td width="198">
<p>OnSiteOrderService</p>
</td>
<td width="141">
<p>ایجاد دو تابع جدید</p>
</td>
<td width="292">
<p>از آنجا که این کلاس از واسط OrderService استفاده می کند، با اضافه کردن متدهای مربوط به موبایلُ نیاز داشتیم که آن دو را در این کلاس هم قرار دهیم ولی با بدنه خالی.</p>
</td>
</tr>

<tr>
<td width="64">
<p><strong>۳</strong></p>
</td>
<td width="198">
<p>OnlineOrderService</p>
</td>
<td width="141">
<p>ایجاد دو تابع جدید</p>
</td>
<td width="292">
<p>از آنجا که این کلاس از واسط OrderService استفاده می کند، با اضافه کردن متدهای مربوط به موبایلُ نیاز داشتیم که آن دو را در این کلاس هم قرار دهیم ولی با بدنه خالی.</p>
</td>
</tr>

<tr>
<td width="64">
<p><strong>۴</strong></p>
</td>
<td width="198">
<p>OrderService</p>
</td>
<td width="141">
<p>ایجاد دو تابع جدید</p>
</td>
<td width="292">
<p>برای حالت موبایل نیاز بود که دو متد جدید اضافه شود تا در کلاس مربوطه پیاده شوند.</p>
</td>
</tr>

<tr>
<td width="64">
<p><strong>۵</strong></p>
</td>
<td width="198">
<p>Main</p>
</td>
<td width="141">
<p>یک else if جدید برای ثبت سفارش با موبایل</p>
</td>
<td width="292">
<p>نیاز بود تا ۳ خط اضافه شود برای ثبت سفارش با موبایل که در ان یک instance از PhoneOrderService گرفته می شود و متد phoneOrderRegister آن صدا زده می شود.</p>
</td>
</tr>

<tr>
<td width="64">
<p><strong>۶</strong></p>
</td>
<td width="198">
<p>Main</p>
</td>
<td width="141">
<p>یک else if برای پرداخت با موبایل</p>
</td>
<td width="292">
<p>نیاز بود تا ۲ خط اضافه شود برای پرداخت با موبایل که در آن متد phoneOrderPayment صدا زده می شود و جمع کل مبلغ به آن پاس داده می شود.</p>
</td>
</tr>

</tbody>
</table>

مجموع تعداد تغییرات: ۶ تغییر اصلی که معادل ۹ تغییر جزیی است.

مجموع تعداد خط اضافه شده: ۶۳ خط