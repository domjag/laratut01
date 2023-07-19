Get this course from Bitfumes youtube channel
Project Idea
1. [x] User can create a new help ticket
3. [ ] Admin can reject or resolve the ticket
2. [ ] Admin and user can reply on help ticket
4. [ ] When admin update on the ticket then user will get one notification via email that ticket status is updated
5. [x] User can give ticket title and description
6. [x] User can upload a document like pdf or image
7. [ ] Table Structure

Tickets

1. [x] title( string ) {required}
2. [x] description(text) {required}
3. [ ] status(open {default}, resolved, rejected)
4. [x] attachment(string) {nullable}
5. [ ] user_id {required} filled by laravel
6. [ ] status_changed_by_id {nullable}

Replies

1. [ ] body(text) {required}
2. [ ] user_id {required} filled by laravel
3. [ ] ticket_id {required} filled by laravel