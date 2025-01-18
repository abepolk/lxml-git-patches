# lxml-git-patches
A repo for patches that can be applied to the Python library lxml
## `print_error_node_info.patch`
A patch that prints out information on lxml errors via libxml2's native debugging features. It prints information about the the node on the top of the node stack when libxml2's HTML parser generates errors. For more information, see the accompanying article on Medium. It can be applied to [the lxml repo](https://github.com/lxml/lxml), as of January 18, 2025 on commit c58e3de.