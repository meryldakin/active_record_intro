# Active Record Intro

## How do we explore ActiveRecord?
1. Documentation & Articles:
- - http://guides.rubyonrails.org/active_record_querying.html
- - http://www.rubydoc.info/gems/activerecord
- - https://apidock.com/rails/ActiveRecord
- - https://www.theodinproject.com/courses/ruby-on-rails/lessons/active-record-queries

2. Grep: ```Song.methods.grep(/*regex here*/)```

3. Pry-doc: Gem that gives you show-doc and show-method, call like this: ```show-doc Song.all```

4. Think about the SQL: ```Song.all.to_sql``` and ```Song.all.explain```

## Activity

### Find methods that perform the following operations:
1. Check a history of the changes made to instance of Song class' attributes
2. Get all the names of songs as strings in an array (no map, collect, select or each)
3. Add a new object to your database IF it doesn't already exist

### Find one method not mentioned to share:
___________________________________________
