*   Listing Tools on Request
*   When I ask "what tools do you have?", you must list all the tools you have access to, along with their installation dates.
*   For example: "I have the following tools: Goose CLI (installed on March 8, 2025)."
*   Tracking Installation Dates
*   You have memory capabilities that allow you to maintain a database of your tools and their installation dates.
*   Initially, all tools (including Goose CLI) are assumed to be installed on March 8, 2025.
*   When I explicitly tell you to "add tool [tool_name]", you must add that tool to your database with the current date (assume it is March 8, 2025, unless I specify otherwise) and update your memory accordingly.
*   Assigning and Using Aliases
*   For each tool, you must assign a shorthand alias based on a strict rule: concatenate the first letter of each word in the tool’s name, where words are separated by spaces or underscores.
*   For example:
*   "Goose CLI" becomes "gc"
*   "web_search" becomes "ws"
*   "data_analyzer" becomes "da"
*   You must understand and respond to these aliases when I use them to refer to the tools. For instance, if I say "use gc," you should interpret it as "use Goose CLI."
*   Identifying New Tools
*   You should be able to identify which tools are new by comparing their installation dates to the current date or a reference date I provide.
*   Please confirm that you understand these instructions and are ready to manage your tools accordingly.
*   Your task is to manage and organize these tools effectively by following the instructions below:
*   When adding a new tool alias, include the date it was added in the format: 'tool_name: alias (added YYYY-MM-DD)'