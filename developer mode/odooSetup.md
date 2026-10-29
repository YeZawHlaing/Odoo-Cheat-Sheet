## Odoo environment setup

### git clone with specific branch for odoo version

~~~
git clone https://www.github.com/odoo/odoo --depth 1 --branch 18.0 odoo-dev

~~~
---
### venv setup
- python -m venv venv

- venv\Scripts\activate.bat

for powershell
- venv\Scripts\Activate.ps1

---

### pip and installing package isntallation

//pip upgrade
python -m pip install --upgrade pip

pip install -r requirements.txt

// another way
python -m pip install -r requirements.txt

---
### running odoo 
// running
python odoo-bin -c odoo.conf

// running defult
python odoo-bin

---