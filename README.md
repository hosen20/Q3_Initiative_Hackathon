# N2H2 Gap Energy Calculation

Diazene (N₂H₂) is a key intermediate in the multi-step reduction of dinitrogen (N₂) to ammonia (NH₃), appearing after initial proton-coupled electron transfers and before further hydrogenation to hydrazine and ammonia2. Determining its gap energy—the difference between ground and first excited states—helps identify photocatalysts capable of efficiently driving these transformations under light, optimizing energy input and reaction selectivity.

80% of ammonia produced per year is used in the production of fertilizers. By building better photocatalysts, the production rate of ammonia becomes faster and more efficient.

More information can be found in the following link: https://www.thyssenkrupp.com/en/stories/sustainability-and-climate-protection/ammonia-in-agriculture:-the-engine-of-plant-growth

Two algorithms (QSE & SS-VQE) are implemented to find the ground and first excited states energies of a simple H₂ molecule. Then QSE is used to find this gap energy of a more complex molecule Diazene N₂H₂.

## Setup Instructions

#### 1. **Clone the Repository**

   Open your terminal or command prompt and run the following command to clone the repository:

   ```bash
   git clone 
```
Navigate into the project directory:
```bash
cd 
```
#### 2. **Create a Python Virtual Environment**
Create a virtual environment to manage dependencies:

```bash
python -m venv venv
```
#### 3. **Activate the Virtual Environment**
On Windows:
```bash
venv\Scripts\activate
```
On macOS and Linux:
```bash
source venv/bin/activate
```
#### 4. **Install Dependencies**
Install the required dependencies listed in the ['requirements.txt'] file:
```
pip install -r requirements.txt
```

## Usage of the Project

Q3_Initiative_Hackathon/
```bash
│
├── 1.SSVQE_H2.ipynb                           # jupyter notebook solution of H2 using SSVQE
├── 2.QSE_H2.ipynb                             # jupyter notebook solution of H2 using QSE
├── 3.QSE_N2H2.ipynb                           # jupyter notebook solution of N2H2 using QSE
├── README.md                                  # Project overview and documentation
├── Presentation.pdf                           # Project video slides in pdf format 
├── Presentation.pptx                          # Project video slides in powerpoint format
├── LICENSE                                    # License for use and distribution

```
