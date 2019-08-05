# Arie-Backend
API being specifically build for Arie application
<b> API Guide </b>
 * Routes in this API, by order
 * POST tasks : create new task
 * GET tasks/?idx= & count= : retrieve general info of number of tasks
 * (including custom parameters to search)
 * GET tasks/:taskID : retrieve details of a particular task
 * PATCH tasks/:taskID : edit existing task
 * DELETE tasks/:taskID?userID= : delete existing task
 * POST tasks/:taskID?userID= : subscribe to a task