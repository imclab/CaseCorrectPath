This code simulates a case-sensitive file system on a case-insensitive one. If you need the opposite, try http://github.com/OneSadCookie/fcaseopen

// Takes an input_path that is known to exist // e.g. "DaTa/fILE.zIP"
// Fills correct_case with the true file path case // e.g. "Data/File.zip"
// Returns whether or not input_path == correct_case
bool IsPathCaseCorrect(const std::string& input_path, std::string *correct_case);

MIT license.