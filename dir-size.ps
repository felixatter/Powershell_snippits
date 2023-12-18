$output = "D:\C-local\system tracking\bigfiles.csv" #path to location of report CSV
$input = "R:\" #drive or dir you want to evaluate.
echo "this report is on files and folders located in, $input." |tee $output
echo "folder\file,size in GB" | tee -Append $output
Get-ChildItem ($input) | foreach{
    $size = (Get-ChildItem  $_.FullName -Recurse | Measure-Object -Property Length -Sum).Sum / 1Gb 
    $sizeR=([math]::Round($size,2)) #rounds to 2 significant figures
    echo "$_,$sizeR" | tee -Append $output #outputs data as size in GB and folder/file name 
    }
