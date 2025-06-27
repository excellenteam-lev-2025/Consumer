# Consumer
צרו בעצמכם תוכנית Producer/Consumer המלאה, שמשתמשת ב־std::mutex וב־std::condition_variable לתיאום.

הוסיפו בדיקה שימנעו deadlock (למשל, נעילת mutex אחד בכל פעם, או שימוש ב־std::scoped_lock לשני mutexים).

ודאו שאין race conditions על משתנים משותפים (למשל, שימוש ב־std::atomic או lock_guard).

הריצו בתרחישים של מספר צרכנים וצרו תרחיש עומס כדי להתרשם מהתנהגות התור.
