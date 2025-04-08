# A Replication of _Embedding Regression: Models for Context-Specific Description and Inference_ (Rodriguez et al., 2023)

## Description

This repository includes materials to replicate key findings from **Rodriguez, Pedro L., Arthur Spirling, and Brandon M. Stewart. 2023. "Embedding Regression: Models for Context-Specific Description and Inference." *American Political Science Review* 117 (4): 1255-1274. doi: 10.1017/S0003055422001228.** It includes links to the original paper and authors' replication materials, our replication materials, and our findings presentation and report.

## Repository Structure & File Contents

<table>
	<thead>
    		<tr>
	      		<th>Folder</th>
	      		<th>Folder Description</th>
			<th>Included File</th>
			<th>File Description</th>
    		</tr>
  	</thead>
  	<tbody>
    		<tr>
        		<td><tt>01_OriginalPaper</tt></td>
			<td>Includes readme file with link to original Rodriguez et al., 2023 paper </td>
			<td><tt>readme.txt</tt></td>
			<td>Links to original Rodriguez et al., 2023 paper</td>
    		</tr>
		<tr>
        		<td rowspan="2"><tt>02_DataverseMaterials/dataverse_files</tt></td>
			<td rowspan="2">Includes readme file with link to Rodriguez et al.'s paper replication materials hosted on Harvard Dataverse website; includes files for extension</td>
			<td><tt>readme.txt</tt></td>
			<td>Links to Rodriguez et al.'s paper replication materials hosted on Harvard Dataverse website</td>
    		</tr>
            <td><tt>wv_*.csv</tt></td>
			<td>Word embedding vectors for the focal word (empire) for Congressional Records (cr) and Parliamentary Speeches (ps) before (pre) and after (post) 1949 to use in cosine similarity calculation.</td>
    		</tr>
    		<tr>
        		<td rowspan="10"><tt>03_Replication</tt></td>
			<td rowspan="10">Includes Bartlett & Sullivan's replication materials</td>
			<td><tt>00_alc_context_exemplar.qmd</tt></td>
			<td>QMD script to replicate "Framework in Action"</td>
    		</tr>
    		<tr>
        		</td><td><tt>00_alc_context_exemplar.html</tt></td>
			<td>HTML output from running <tt>00_alc_context_exemplar.qmd</tt> script; presents code collated alongside output</td>
		</tr>
        <tr>
        		</td><td><tt>01_use_case1_group_meanings.qmd</tt></td>
			<td>QMD script to replicate framework use case 1</td>
		</tr>
        <tr>
        		</td><td><tt>01_use_case1_group_meanings.html</tt></td>
			<td>HTML output from running <tt>01_use_case1_group_meanings.qmd</tt> script; presents code collated alongside output</td>
		</tr>
        <tr>
        		</td><td><tt>02_use_case2_temporal_changes.qmd</tt></td>
			<td>QMD script to replicate framework use case 2</td>
		</tr>
        <tr>
        		</td><td><tt>02_use_case2_temporal_changes.html</tt></td>
			<td>HTML output from running <tt>02_use_case2_temporal_changes.qmd</tt> script; presents code collated alongside output</td>
		</tr>
        <tr>
        		</td><td><tt>02a_use_case2_extension.qmd</tt></td>
			<td>QMD script to execute validation</td>
		</tr>
        <tr>
        		</td><td><tt>02a_use_case2_extension.html</tt></td>
			<td>HTML output from running <tt>02a_use_case2_extension.qmd</tt> script; presents code collated alongside output</td>
		</tr>
		<tr>
        		</td><td><tt>bootstrap.css</tt></td>
			<td>CSS code called in QMD files for HTML formatting</td>
		</tr>
        <tr>
        		</td><td><tt>/_plots</tt></td>
			<td>Plots replicated from analyses; called in <tt>Bartlett-Sullivan-replication-2-presentation.qmd</tt></td>
		</tr>
  		<tr>
        		<td rowspan="5"><tt>04_Presentation</tt></td>
			<td rowspan="5">Includes presentation materials</td>
			<td><tt>Bartlett-Sullivan-replication-2-presentation.qmd</tt></td>
			<td>QMD script to produce presentation</td>
    		</tr>
    		<tr>
        		</td><td><tt>Bartlett-Sullivan-replication-2-presentation.html</tt></td>
			<td>Presentation given on 4/3/25</td>
		</tr>
        <tr>
        		</td><td><tt>semantic_shift_walkthrough.qmd</tt></td>
			<td>QMD walk-through of "Framework in action" as part of presentation (Rodriguez et al. analytic code + Bartlett, Sullivan formatting) </td>
		</tr>
        <tr>
        		</td><td><tt>semantic_shift_walkthrough.html</tt></td>
			<td>HTML output from running <tt>semantic_shift_walkthrough.qmd</tt></td>
		</tr>
		<tr>
        		</td><td><tt>bootstrap.scss</tt></td>
			<td>CSS code called in <tt>Bartlett-Sullivan-replication-2-presentation.qmd</tt> for HTML formatting in <tt>Bartlett-Sullivan-replication-2-presentation.html</tt></td>
		</tr>
  		<tr>
        		<td rowspan="2"><tt>05_FinalReport</tt></td>
			<td rowspan="2">Includes final paper materials</td>
			<td><tt>Bartlett-Sullivan-replication-2-paper.rmd</tt></td>
			<td>RMD script to produce <tt>Bartlett-Sullivan-replication-2-paper.pdf</tt></td>
    		</tr>
    		<tr>
        		</td><td><tt>Bartlett-Sullivan-replication-2-paper.pdf</tt></td>
			<td>Bartlett & Sullivan final paper</td>
		</tr>

</table>

## Authors

Maria Bartlett & Bridgette Sullivan

## Course & Institutional Information

This project was produced as part of the spring 2025 **PPOL 6801: Text as Data: Computational Linguistics** course at **McCourt School of Public Policy** at **Georgetown University**.

## References

Rodriguez, Pedro L., Arthur Spirling, and Brandon M. Stewart. 2023. "Embedding Regression: Models for Context-Specific Description and Inference." *American Political Science Review* 117 (4): 1255-1274. doi: 10.1017/S0003055422001228

Rodriguez, Pedro L.; Spirling, Arthur; Stewart, Brandon M., 2023, "Replication Data for: Embedding Regression: Models for Context-Specific Description and Inference", https://doi.org/10.7910/DVN/NKETXF, Harvard Dataverse, V1, UNF:6:gBkWkhpPxkGmXEddHggmJQ==[fileUNF]
