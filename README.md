# data_analysis_toturial
تو این پروژه اومدیم یه دیتای خیالی رو با هم ایجاد و براش کوئری نوشتم با شرط های گوناگون

فکر کنم این روش برای آپلود روی گیت هاب با دستورات گیت بهتر باشه:

# نصب Git
!apt install git -y

# تنظیمات Git
!git config --global user.email "you@example.com"
!git config --global user.name "Your Name"

# کلون کردن ریپازیتوری
!git clone https://github.com/username/data-analysis-demo.git

# کپی فایل به پوشه‌ی ریپو
!cp sales_data.csv data-analysis-demo/

# رفتن به دایرکتوری ریپو
%cd data-analysis-demo

# اضافه کردن فایل به گیت
!git add .

# کامیت کردن
!git commit -m "Add sales data analysis"

# پوش کردن به گیت‌هاب
!git push
