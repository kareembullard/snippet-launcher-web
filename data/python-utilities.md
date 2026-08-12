# csv_utils.md

# Module `csv_utils` Documentation

## `sanitize_filename`
### Description
Sanitize a string to make it a valid file or folder name.

Parameters:
- name (str): Original name.

Returns:
- str or None: Sanitized name or None if invalid.

## `select_file_or_directory`
### Description
Opens a dialog to select the input file or directory.

## `csv_to_json`
### Description
Converts a CSV file to a JSON file.

## `select_file`
### Description
Opens a dialog to select the input file.

## `read_csv_file`
### Description
Reads a CSV file into a pandas DataFrame.

## `write_csv_file`
### Description
Writes a pandas DataFrame to a CSV file.

## `read_csv_with_progress`
### Description
Reads a csv file with progress tracking.

## `csv_to_json`
### Description
Converts a CSV file to a JSON file.

## `fetch_Coda.io_data`
### Description
Fetches all records from a specified Coda.io table.

## `parse_json_data`
### Description
Parses JSON data from a file.

## `generate_weekly_newsletter`
No docstring available.

## `update_Coda.io_fields`
### Description
Updates fields in a Coda.io Table.

## `is_csv`
### Description
Checks if a file is a CSV file based on extension.

## `generate_weekly_newsletter`
No docstring available.

## `update_Coda.io_fields`
No docstring available.



# data_utils.md

# Module `data_utils` Documentation

## `generate_blog_post_from_ai`
### Description
Generates a blog post using OpenAI.

## `fetch_feed_data`
### Description
Fetches data from an XML feed.

## `parse_xml_data`
### Description
Parses XML data from a file.

## `fetch_feed_data`
No docstring available.

## `generate_blog_post`
No docstring available.



# file_utils.md

# Module `file_utils` Documentation

## `process_file`
### Description
Processes a single CSV file uploaded through Flask.

## `clean_and_sort_csv_files`
### Description
Cleans all CSV files in a folder by removing empty columns and columns containing ['rec'],
then sorting columns from left to right by the number of non-empty entries.

Parameters:
    folder_path (str): Path to the folder containing the CSV files.

## `clean_csv_files`
### Description
Cleans all CSV files in a folder by removing any column where ['rec'] appears more than 10 times.

Parameters:
    folder_path (str): Path to the folder containing the CSV files.

## `process_markdown_files`
### Description
Process all text files in a directory, converting Markdown to plain text.

Parameters:
- directory (str): Path to the directory containing text files.

## `convert_md_to_txt`
### Description
Converts a Markdown (.md) file to a .txt file.

## `convert_all_md_to_txt`
### Description
Converts all .md files in a directory (and its subdirectories) to .txt files.
Ensures no overwrite by creating unique names for output files.

## `copy_txt_files_and_folders`
### Description
Copies all folders and .txt files from the source directory to the destination directory.
Maintains the directory structure.

## `create_folders`
No docstring available.

## `create_folders_from_list`
### Description
Creates a directory with folders based on the items listed in a text file.

Args:
    txt_file_path (str): The path to the text file containing the list.
    base_dir (str): The base directory where the folders will be created.

## `create_directory_structure`
No docstring available.

## `process_file`
No docstring available.

## `process_directory`
### Description
Processes all CSV files in a given directory.

## `process_file`
No docstring available.

## `process_directory`
### Description
Processes all CSV files in a given directory.

## `split_csv_by_headers`
### Description
Splits a CSV file into multiple files based on headers.

## `process_file`
No docstring available.

## `process_file`
No docstring available.

## `split_csv_by_column`
### Description
Splits a CSV file into multiple files based on the values of a given column.

## `convert_docx_to_txt`
### Description
Converts a .docx file to a .txt file using python-docx.

## `convert_all_docs_to_txt`
### Description
Converts all .doc and .docx files in a directory (and its subdirectories) to .txt files.
Keeps both files and ensures no overwrite by creating unique names.

## `convert_files`
### Description
Converts .md, .doc, and .docx files in a directory to .txt files.

## `run_conversion`
No docstring available.

## `convert_files`
### Description
Converts files in a directory.

## `run_conversion`
No docstring available.

## `is_image`
### Description
Checks if a file is an image using magic.

## `get_filename_without_extension`
### Description
Extracts the filename without the extension.

## `change_file_extension`
### Description
Changes the extension of a file path.

## `get_all_files_in_directory`
### Description
Gets a list of all files within a directory.

Args:
    directory_path (str): Path to the directory.
    extensions (list of str, optional): List of file extensions to filter by (e.g., ['.txt', '.csv']). Defaults to None (all files).
    recursive (bool, optional): Whether to search recursively in subdirectories. Defaults to True.

Returns:
    list of str: List of absolute file paths.

## `get_all_directories_in_directory`
### Description
Gets a list of all directories within a directory.

## `remove_empty_directories`
### Description
Removes empty directories recursively.

## `create_nested_directory_structure`
### Description
Creates a nested directory structure based on a dict.

## `move_file`
### Description
Moves a file from source to destination.

## `copy_file`
### Description
Copies a file from source to destination.

## `batch_rename_files`
### Description
Renames files in a directory using regex.

## `process_files_with_colon_formatting`
### Description
Process all text files in a directory, formatting lines with colons.

Parameters:
- directory (str): Path to the directory containing text files.

## `process_markdown_files_with_colon`
### Description
Process all text files in a directory, converting Markdown to plain text with colon formatting.

Parameters:
- directory (str): Path to the directory containing text files.

## `insert_content_line`
### Description
Inserts a line containing 'Content: ' after every line that contains 'Date: '.

Args:
    file_path (str): The path to the input text file.
    output_path (str, optional): The path to the output text file.
                                 If not provided, the original file will be overwritten.

## `traverse_directory`
No docstring available.

## `merge_md_files`
### Description
Merges all .md files in the specified directory into one file.

Parameters:
    directory (str): Path to the directory containing .md files.
    output_file (str): Path for the output .md file.

## `merge_csvs_by_prefix_into_workbooks`
### Description
Merges CSV files that start with the same prefix into separate Excel workbooks.

Parameters:
    folder_path (str): Path to the folder containing the CSV files.
    output_folder (str): Path to save the resulting Excel workbooks.

## `merge_csvs_to_excel`
### Description
Merges all CSV files in a folder into an Excel workbook.

Parameters:
    folder_path (str): Path to the folder containing the CSV files.
    output_file (str): Path to save the resulting Excel workbook.

## `extract_python_elements(directory)`
### Description
Extracts unique functions, classes, and variables from Python files in a directory.

## `create_module_file`
### Description
Creates a module file with the given elements.

## `create_package`
### Description
Creates a package with the extracted modules.

## `create_docs(package_name,`
### Description
Creates documentation files for the modules.

## `classify_code(elements)`
No docstring available.

## `merge_folders`
No docstring available.

## `create_projects`
No docstring available.

## `create_directory`
### Description
Create a directory if it doesn't exist.

## `move_folder`
### Description
Move a folder from old_path to new_path.

## `update_projects`
No docstring available.

## `count_words_and_characters_in_directory`
### Description
Count words and characters in all files within a directory.

## `count_words_in_directory`
No docstring available.

## `count_words_in_directory`
No docstring available.

## `convert_docx_to_txt`
### Description
Converts a .docx file to a .txt file using python-docx.

## `create_docs`
### Description
Creates documentation files for the modules.



# text_utils.md

# Module `text_utils` Documentation

## `csv_to_formatted_txt`
### Description
Converts a CSV file to a formatted text file.

## Code Snippet
```python
@app.route('/convert', methods=['POST'])
def convert_csv():
    """Handles the conversion of CSV files to formatted text."""
    try:
        logging.info('Received /convert request')
        if 'file' in request.files:
            uploaded_file = request.files['file']
            logging.info(f'Processing single file: {uploaded_file.filename}')
            output_location = process_file(uploaded_file)
            return jsonify({'message': 'Conversion successful.', 'output': output_location})
        elif 'files' in request.files and 'directory' in request.form:
            files = request.files.getlist('files')
            directory = request.form['directory']
            logging.info(f'Processing directory: {directory}')
            output_location = process_directory(directory, files)
            return jsonify({'message': 'Conversion successful.', 'output': output_location})
        else:
            logging.warning('No file or files provided')
            return (jsonify({'error': 'No file or files provided'}), 400)
    except Exception as e:
        logging.error(f'Error in conversion: {e}', exc_info=True)
        return (jsonify({'error': str(e)}), 500)
```

## `markdown_to_plaintext`
### Description
Convert Markdown text to plain text by removing or replacing Markdown syntax.

Parameters:
- text (str): The Markdown-formatted text.

Returns:
- str: The plain text.

## `csv_to_formatted_txt`
### Description
Converts a CSV file to a formatted text file.

## `apply_custom_transformation`
### Description
Applies a custom transformation function to a CSV file.

## `run_action`
No docstring available.

## `update_transformation_text`
No docstring available.

## `csv_to_formatted_txt`
### Description
Converts a CSV file to a formatted text file.

## `apply_custom_transformation`
### Description
Applies a custom transformation function to a CSV file.

## `csv_to_formatted_txt`
### Description
Converts a CSV file to a formatted text file.

## `main_newsletter`
No docstring available.

## `convert_doc_to_txt_with_pywin32`
### Description
Converts a .doc file to a .txt file using pywin32 to automate Microsoft Word.

## `doc_to_txt`
### Description
Converts a Word (.doc) file to plain text (.txt) using pypandoc.

## `txt_to_doc`
### Description
Converts a plain text file to .doc using pypandoc

## `format_colon_lines`
### Description
Format text such that:
- Lines with a colon are split into a bold heading and content on a new line.

Parameters:
- text (str): The input text.

Returns:
- str: The formatted text.

## `markdown_to_plaintext_with_colon_formatting`
### Description
Convert Markdown text to plain text with custom formatting:
- Add a line break after colons followed by a space.
- Make lines with colons bold or headings.

Parameters:
- text (str): The Markdown-formatted text.

Returns:
- str: The formatted text.

## `main`
No docstring available.

## `main`
No docstring available.

## `remove_non_alphanumeric`
### Description
Removes all characters except letters, numbers, and spaces.

## `wrap_text`
### Description
Wraps text to a specific line width.

## `replace_multiple_spaces`
### Description
Replaces multiple spaces with a single space.

## `extract_email_addresses`
### Description
Extracts email addresses from a string using regular expressions.

## `markdown_to_plaintext`
### Description
Convert Markdown text to plain text by removing or replacing Markdown syntax.

## `extract_links`
### Description
Extracts all links from markdown formatted text.

## `remove_images`
### Description
Removes images from markdown text.

## `format_colon_lines`
### Description
Format text such that:
- Lines with a colon are split into a bold heading and content on a new line.

## `extract_text_from_doc`
### Description
Converts a .doc file to a .txt file using pywin32 to automate Microsoft Word.

## `get_document_metadata`
### Description
Extracts metadata from a docx or doc file.

## `convert_docx_to_pdf`
### Description
Converts a docx file to a pdf file.

## `convert_doc_to_txt_with_pywin32`
### Description
Converts a .doc file to a .txt file using pywin32 to automate Microsoft Word.



# word_utils.md

# Module `word_utils` Documentation

## `convert_docx_to_txt`
No docstring available.

## `is_word_installed`
### Description
Checks if Microsoft Word is installed and accessible.

## `cleanup_word_instances`
### Description
Ensures that all Word instances are closed when the script exits.

## `docx_to_txt`
### Description
Converts a Word (.docx) file to plain text (.txt).

## `txt_to_docx`
### Description
Converts a plain text (.txt) to a word docx file(.docx)

## `extract_all_text_from_docx`
### Description
Extract all text content from a .docx file.

## `extract_tables_from_docx`
### Description
Extract tables from a .docx file and returns them in a dictionary.

## `replace_text_in_docx`
### Description
Replaces all occurrences of text in a docx file.

## `close_all_word_processes`
### Description
Ensures that all Word instances are closed when the script exits.

## `kill_long_running_word_processes`
### Description
Kills Word processes that have been running longer than max_runtime_seconds.

## `main`
No docstring available.



