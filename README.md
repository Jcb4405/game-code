game-code
=========
GitHub · Build software better, together.

# An Uncrustify configuration file to match the

# official raywenderlich.com Objective-C style guide.

#

# https://github.com/raywenderlich/objective-c-style-guide

#

# General options

newlines = auto

input_tab_size = 2

output_tab_size = 2

string_escape_char = 92

string_escape_char2 = 0

tok_split_gte = false

utf8_bom = remove

utf8_byte = false

utf8_force = false

# Objective-C stuff

indent_oc_block = true

indent_oc_block_msg = 0

indent_oc_msg_colon = 0

sp_after_oc_scope = force

sp_after_oc_colon = remove

sp_before_oc_colon = remove

sp_after_oc_dict_colon = force

sp_before_oc_dict_colon = remove

sp_after_send_oc_colon = remove

sp_before_send_oc_colon = remove

sp_after_oc_type = remove

sp_after_oc_return_type = remove

sp_after_oc_at_sel = remove

sp_after_oc_at_sel_parens = add

sp_inside_oc_at_sel_parens = remove

sp_before_oc_block_caret = ignore

sp_after_oc_block_caret = remove

sp_after_oc_msg_receiver = remove

sp_after_oc_property = force

# Indenting

indent_columns = 2

indent_continue = 2

indent_with_tabs = 0

indent_cmt_with_tabs = false

indent_align_string = false

indent_xml_string = 0

indent_brace = 0

indent_braces = false

indent_braces_no_func = false

indent_braces_no_class = false

indent_braces_no_struct = false

indent_brace_parent = false

indent_namespace = false

indent_namespace_level = 0

indent_namespace_limit = 0

indent_extern = true

indent_class = true

indent_class_colon = false

indent_ctor_init_leading = 2

indent_ctor_init = 0

indent_else_if = false

indent_var_def_blk = 0

indent_var_def_cont = false

indent_func_def_force_col1 = false

indent_func_call_param = false

indent_func_def_param = false

indent_func_proto_param = false

indent_func_class_param = false

indent_func_ctor_var_param = false

indent_template_param = false

indent_func_param_double = false

indent_func_const = 0

indent_func_throw = 0

indent_member = 0

indent_sing_line_comments = 0

indent_relative_single_line_comments = false

indent_switch_case = 0

indent_case_shift = 0

indent_case_brace = 0

indent_col1_comment = false

indent_label = 1

indent_access_spec = 1

indent_access_spec_body = false

indent_paren_nl = false

indent_paren_close = 0

indent_comma_paren = false

indent_bool_paren = false

indent_first_bool_expr = false

indent_square_nl = false

indent_preserve_sql = false

indent_align_assign = true

# Spacing

sp_inside_paren = remove

sp_paren_brace = force

sp_before_ptr_star = force

sp_before_unnamed_ptr_star = ignore

sp_between_ptr_star = remove

sp_after_ptr_star = remove

sp_func_call_paren = remove

nl_after_func_body = 2

eat_blanks_after_open_brace = true

eat_blanks_before_close_brace = true

# Newlines

nl_assign_leave_one_liners = true

nl_enum_brace = remove

nl_struct_brace = remove

nl_union_brace = remove

nl_if_brace = remove

nl_brace_else = remove

nl_elseif_brace = remove

nl_else_brace = remove

nl_else_if = remove

nl_for_brace = remove

nl_while_brace = remove

nl_func_decl_end = remove

nl_func_def_end = remove

nl_fcall_brace = remove

nl_fdef_brace = remove
